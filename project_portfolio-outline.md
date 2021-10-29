# Portfolio Site
Project Goal: To create an attractive & original portfolio website.

**Ideas**
1. Roy Lichtenstein style with Ben-Day Dots in dropshadows etc. Animated comic characters appearing on screen with speech bubbles etc.
2. An Ubuntu style desktop with panel on lefthand side and pseudo app menu with projects in place of apps.

Choice: No.2, the Ubuntu desktop style

## Stage 1: HTML & CSS w/ Basic/Minimal JS
The goal of stage 1 is to have the following:
1. An Ubuntu-style desktop with lefthand panel
	- Mobile version will be similar to Ubuntu Touch
2. Pseudo apps on panel that will open, for example, a contact form, the app menu, bio/work history
3. An app menu page with zoom in animation a-la gnome3, which contains links to project pages (no less than 2, no more than 4)
4. Clicking on a project will open a pseudo-browser window with details info about the project (goals, stages, problems, lessons learned, screenshots, technologies used)
	- Pseudo browser window should have a close button at top right which will return you to the desktop
5. A contact form styled like an email app window
6. Hamburger menu on mobile version should have a fun animation which converts the three hamburger lines into a left pointing arrow and vice versa

MAYBE: Have links for Github/LinkedIn on panel which will open those sites in an iframe?

### A11y
Website must be as accessible as possible. Run through all available audit tools. Populate ARIA roles etc. If some features are not accessibility friendly implement a "toggle" which will swap between a more basic version that is more accessible and the full version which is not.