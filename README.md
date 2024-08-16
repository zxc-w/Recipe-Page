## Frontend Mentor Challenge [4] - Recipe Page

![Challenge](preview.jpg)

The challenge is to implement this design and make it responsive to different screen sizes.

## Preview

[Desktop Preview](./design/desktop-design.jpg)
\
[Mobile Preview](./design/mobile-design.jpg)

## Project Insights

I learned a lot from this challenge.

Had different issues in CSS:

- Adjusting the space between the list items and its markers.

  - This requires using the list styling `list-style-type:none` and using `::before` pseudo selector to make the markers myself so I can manage them as I want and adjust the spacing as needed.

- In the mobile design, the image is full width which I didn't notice at first and my styling needed some refactoring to make it work in both desktop and mobile views.

- A weird behaviour of the `body` element's height isn't enough for the content inside it which causes overflow and layout issues although its height property was set to `100%`. Changing the `height` to `auto` resolved this issue.

  - This causes **no** margin or any space around the body content which makes the content stick to the edges but I needed the content to breath a little. So, I used margin with a percentage value to the `main` element which is much better now.

Overall, I'm happy with the result.

Hope you are too!

## Live Deployment

Check out the live site on Github Pages: [Recipe Page](https://zxc-w.github.io/Recipe-Page)
