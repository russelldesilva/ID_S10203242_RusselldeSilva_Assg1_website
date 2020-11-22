# ID_S10203242_RusselldeSilva_Assg1_repository
ID Assignment 1
This website is a personal portfolio website for myself. Its user audience would be future job recruiters looking to hire me to their company.

The website will serve as an exhibition of the various projects and achievements I have completed or earned throughout my schooling life. It will also highlight my education and work experience, which will be useful for job recruiters viewing my website.
It should be readable and easy-to-navigate to ensure users have a good experience while browsing.

Design Process
This website is for myself. Its aim is to present myself in the best light for the user audience to hire me. As I would like make a career in the IT sector in the future, a website would be a great way to display my IT skills as well as allow the hiring recruiters to know more about me. It allows me to include all my projects and achievements in a format that is easily accessible by anyone, and enables me to express my creativity 

User Stories
- As a job recruiter, I want to view the applicant's educational history so that I can check if he is qualified for the job
- As a job recruiter, I want to view the applicant's work experience to evaluate how experienced he/she is and see what skills he/she posesses. 
- As a job recruiter, I want to view the applicant's portfolio of projects to assess his skill levels in different areas of IT and ability to generate good ideas.
- As a job recruiter, I want to find out more about the applicant's personality to see if he would be a good fit for the company.
Wireframe -> "https://xd.adobe.com/view/b46af37b-aad2-4cd3-a395-801738d02d1a-e139/"


Existing Features
Feature 1 - Skill Proficiency
This consists of a simple <ul> of all the hard skills I have learnt so far (Python, C#, HTML and CSS) and and a correspoding <ul> adjacent to it with my proficiency levels (on a scale of 1 to 10, 10 being extremely proficient). This is a simple and quick way for recruiters to see how skilled I am at certain technologies which may be useful for the job.

Feature 2 - Sticky Nav bar
Navigation bar permanently anchored at top of page (using position: sticky CSS rule) for easier navigation. Users would not have to scroll up to the top of the page every time they want to navigate.

Technologies Used

Adobe XD for wireframe design.
VS Code for HTML/CSS coding.

Testing
When testing the website on different screen sizes, I discovered that some elements (h1-h6) resize automatically when shrinking the screen. So much so that they became unreadable. To counter this, I had to create one more media query than I intende (@media (max-width: 600px)). This ensured that no how small the screen, The font size would remain just right. All possible screen sizes have now been accounted for due to the max width function handling all screen sizes below 600px width and min width function handling all screen sizes above 900px.

Secondly, "scouts.jpg" on education.html does not resize according to its container <header> due to the fact other elements on the page do not resize as well. This results in a lack of space for the image and causing it to be pushed out of the box.

My project looks the same on all major browsers. (Edge, Chrome, Firefox)
However, on Internet Explorer, the nav bar and images are misalingned. This is because it does not support flexboxes.

Credits
Content
The text for About Me section on index.html was copied from the my personal website (made for FP1 assignment) "https://russelldesilva.wordpress.com/".
The text for education.html was copied from my FP1 assignment "Personal Branding" last semester.
Media
LinkedIn picture on index.html: "https://www.flaticon.com/free-icon/linkedin_174857"
St Patrick's School logo: Originally from "https://stpatricks.moe.edu.sg", but image no longer there.
Background image on index.html "https://images.unsplash.com/photo-1516577571543-34730998c489?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=400&q=60".
All other images were from my personal photo gallery.

Acknowledgements
I received inspiration for this project from FP1 personal branding assignment and with a lot of help from w3schools.com!