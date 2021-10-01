# Intro-to-Git-and-Github-OSC
Hi, welcome to the Walkthrough: Git and Github for beginners with the Open Source Club

# List of Restaurant Recommendations in NYC
* Katsuei
* 

<details> 

<summary>README EXAMPLE</summary>

#### based on [Assignment 2: Making &amp; Breaking the Grid - Swiss Poster Design](https://github.com/themiscadiz/Assignment2)
----
<!-- Every README should start with an H1 -->
# Assignment 2: Making &amp; Breaking the Grid - Swiss Poster Design
<!-- A one sentence description of the project or assignment -->
In this project I go through the design process of redesigning a Swiss poster and converting it into a responsive website.

![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/giphy1.gif?raw=true)

<!-- It is good practice to add an about or summary -->
## About

For this assignment I used one of the examples provided in the assignment. I chose the poster above because of its clear grid design. That let me explore the attribute of flex on css and have a better understanding of how to manipulate it into a responsive design. I explored timeanimation for the first time
on css and some functions in javascript.

<!-- It is essential to describe how to set up your project -->
## Setup
To redesign a poster you can setup using: 


<!-- Any knowledge or tools you will need before hand -->
### Prerequisites

To make a good readme the following prerequisites are necessary:
1. A design software program - In this project I used [Figma](https://figma.com/)
2. A text editor - like [VS Code](https://code.visualstudio.com/)
3. Terminal or Command line.

<!-- any installation needs should be defined -->
### Installation

To use your terminal or command line to locally host your website (in case of Mac):
1. Open Terminal 
2. Type <code>cd</code> (don’t forget the space)
3. In Finder, navigate to the folder and  Drag and drop into the Terminal.
4. In Terminal, type: <code>browser-sync start --server -f -w</code>
5. Server should launch, and you should see the correct ip address to navigate to.
   Something like this: localhost:3000

**Notes: There a other ways to open a localhost. This is just my prefered method, because it automatically refreshes the website.**

<!-- Write instructions on how to start working on your project -->
### Develop

To develop this project, you can:
1. Sketch and Design website
2. Develop code into your code editor
3. Follow progress in your localhost

**Note: Instead of a code editor, you can use [Glitch](https://glitch.com) to keep track of your code in real-time.

<!-- Notes about the deployment -->
### Deployment

For a project in progress it is possible to host it on [Glitch](https://glitch.com)
## Built with

* [VS Code](https://code.visualstudio.com/)
* [Glitch](https://glitch.com)
* [Github](https://github.com)

## Authors

* [Themis Garcia](https://github.com/themiscadiz) -- NYU ITP student

<!--## Code of Conduct

<!--Please read the [CODE OF CONDUCT](https://www.mozilla.org/en-US/about/governance/policies/participation/) 

<!--## License

<!--This is README template is licensed according to [Attribution 4.0 International (CC BY 4.0) ](https://creativecommons.org/licenses/by/4.0/)

<!-- thank and reference all the things that made your project happen -->
<!--## Acknowledgements

<!--* [Creative Commons](https://creativecommons.org/licenses/by/4.0/) for their licensing documentation
<!--* [Openmoji project](https://www.openmoji.org/library/#search=notebook&emoji=1F4D4) for their glyphs
<!--* [PurpleBooth's Readme Template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)

***
***
***

<!-- For your assignments you might consider  -->
# Notes & Process
For this assignment I decided to use one of the designs suggested in the assignment post.

![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/1.png?raw=true)

The clear hierarchy and grid, helps me to understand layout organization better. For the redesign exercise, I started from creating a Style Guide of the swiss poster:

**Website about New York**
In the theme of New York, I decided to work with Loisaida. It was the way newyoricans called the Lower East Side. This neighborhood has a rich history of social activism for the newyorican community, specially in the 60's, 70's and 80's. This  website remembers their participants and its contrubution.

**Style guide of Swiss Poster**

![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/4.png?raw=true)

Although I tried to find the font used in this poster, I wasn't able to find a precise answer. The shape of the **G** didn't match with any swiss type style that I found. The closest fonts are Helvetiva and Univers. However this small dive into typograghy gives me an idea about swiss styles.

![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/2.png?raw=true)

<!-- How you built this project - Include images, gifs, and notes here -->
## Process & Documentation

**Sketching**
Sketch helps me to rapidly get the layout of the poster and how approach the redesign for a website.
![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/17.png?raw=true)

**Wireframes**  
This step helped me to start from the style guide of the poster to a make grid decision about the new redesign. For the wireframe and other design decisions I used Figma. Altough was the first time using this software, it was friendly to understand and follow.

![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/15.png?raw=true)

**Design specifications**
For a more detailed design specification I made a style guide with new design.

![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/16.png?raw=true)

**Html and css**
To have a fast feedback about the html and css development I used Glitch. To better understand the developers practice I started my code from last class' live code example. Although throughout the process I made a lot of modifications, this first approach gave me a guideline for html and css practices.

In this sequence of images you can see the process from the first html modification to the style of the layout. This part took me a lot of effort to be able to understand a little bit better how to work with grids and responsive layouts.

![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/7.png?raw=true)
![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/8.png?raw=true)
![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/9.png?raw=true)

The main two columns on the website change into one column, one row design. 
The navegation is 4 item list next to the title "Lower East Side". In the small responsive version this navegation goes below the title.
This flow is used on the other rows on the website.

**Animation on css**

This is my very first time that I tried to animate in css. Using a loop I move the title back and foward, changing the color of the title, and breaking the layout. I had some difficulties using this feature because the movement affected the clickability of the navigation. 
At first, I moved the animation side to side. Although the title wasn't above the navigation, it affected the clickability. I changed the animation to vertical, and in this case affect the navigation when use a smaller screen width. I tried different option but I didn't figure it out how to debug it.

![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/giphy1.gif?raw=true)


**Integration with javascript**
Understanding how to implement javascript was challenging for this assigment. Altough last semester I have used p5.js, I don't have any experience using js outside of p5.
However, I was able to use to js functions such as <code>onload</code>, and <code>click</code> in this website. 

   * When one of the image upload, open a window who welcome the user to the website.

![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/13.png?raw=true)


   * When user mouse clicked "Loisaida" in the navegation, open a window with a definition.
   

![image](https://github.com/themiscadiz/Assignment2/blob/master/Images%20from%20Documentation/14.png?raw=true)

Although I am not sure what it is a better practice,I started the <script> in html, then I moved the function into another file.

<!-- Any specific challenges or struggles documented -->
## Challenges & Struggles

Here I summarized some of the  challenges that I had completing this assigment and detailed above.

*Figuring out font-family of the swiss poster.
*Understanding how to manipulate or use javascript.
*Animation in css


<!-- Any questions you have -->
<!-- ## Questions -->

<!-- References for resources and inspiration -->
## References

* Loisaida -- Wikipedia [https://en.wikipedia.org/wiki/Alphabet_City,_Manhattan#Loisaida]()
  
</details> 
