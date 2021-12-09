![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome rhysmoggs,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **September 1, 2021**

## Software / 

Balsamiq to create the wireframes
used github, gitpod/vs code, html5, css3, bootstrap4, fontawesome5?
used colour picker (link) to take colour from instagram logo, applied as main bg colour/mention colour pallete in different section too.
links to live project, github?
links to sources, software used, 
tinyPNG compressed images
https://www.freeconvert.com/jfif-to-jpg to convert a jfif image to jpg
lighthouse google/chrome
validate code - links to w3 website
google, slack, bootstrap documents, w3 html + css documents

## User Stories
As a first time visitor to the site, I want to easily find the information I need. In particular, I want to easily find a price guide, information on purcahsing cakes and delivery options
etc. I also want to easily find contact information about the company. I want to be able to do this easily on mobile, tablet as well as my laptop. I want to be able to contact the business by social media or directly, and I want that to be very clear and obvious to find.


## Site Owner Goals
I want to bring awareness to the new brand/company, give infomation about the team and our story, to create a connection with our visitors and hopeful customers, and of course to make money via our shop. I want users to interact with us via social media, to follow us and feel that they can contact us on multiple different avenues i.e. social media links and forms through the website.
I want to show off to the visitors of our website that we are a trusted and reputable company, that have had our products showcased in many events, food festivals and shops accross Wales and the UK, and that their money will be well spent on our products.

## Building the Website
Folllowing is the process on how I approached and built the website. I began with creating the file and folder setup/ and then added content to each file, starting with the index.html
Used relative units (rem, check if I used others or need to adjust some) where applicable to ensure the webiste was proportional through all screen sizes. This provides consistency, familiarity and ease-of-use to the websites visitors and ensures the website remains stylistically sound.

### index.html
started with default htmls through ! + tab or !bcpn? for bootstrap filler for ...
added links and scripts to bootstrap and all necessary plugins, fontawesome, google fonts 
began with a quick layout of divs/sections then fleshed out content
navbar

added offer banner on very top of website above the navbar and logo, made a bright and attractive colour to draw the eyes.
removed the hero image to and replaced with two images linking to click and collect and home delivery section/pages on website.
added responsive elements to the shop link images, with them stacking on a smaller device and then displaying side-by-side on medium(larger?) devices and upwards.
I used bootsrtraps col-12 col-md-6 class to do this, (check screen breakpoints) but have intentions to create my own custom css styling and media queries if time permits this.
used custom css to style the buttons

added a bootstrap card but could alter this, for displaying the Meet the Team/About Us section, along with an image of a staff memeber.

footer

### style.css
contains classes, both custom and alterations to bootstraps default classes


## Testing
used Insepct Mode (ctrl shift + i on chrome, windows) to see real-time adjustments and bootstraps own classes. i then tweaked and copied the prferred styling to my own style.css
navbar - constant testing and tweaking to fit logo.png and make clear, along with responsive navbar, including the hamburger-mobile/tablet friendly icon
- logo too large or wrapping out of navbar/container. eventually adjusted height/width correctly and used efault bootstrap navbar from their docs website. responsive down to ~300px and all the way up to xl?
after acheiving a responsive nav bar I was happy with, I then adjusted the navbar-collapse class input of flex-basis: 100% to 0% and adjusted the text-align: center to center the menu options on smaller screens and stack them under the hamburger icon.
container-fluid, removed padding from default bootstrap class using p-0 class.

initial plans of adding a jumbotron with a link to the shop, but instead opted for two large images linking to click and collect and home delivery. clearner and more obvious.
used Inspect Mode often here, to adjust the padding, margins and layout of section.



------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------


**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
