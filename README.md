# Soccer Ball Rain Effect

This HTML file creates a falling soccer ball rain animation using CSS and JavaScript.

How it works:
- A fixed container fills the screen with `#football-rain`.
- JavaScript adds multiple `.football-ball` elements on page load.
- Each ball gets a random size, random horizontal position, and a random fall timing.
- CSS animation moves each ball from above the top of the screen to below the bottom while rotating and fading out.
- If the user prefers reduced motion, the effect is hidden for accessibility.
- After the effect duration, the script removes the container from the page.

Important:
- You must replace `BALL_IMAGE_URL` in the CSS with the actual soccer ball image URL.
- The background image is used for each falling ball.
