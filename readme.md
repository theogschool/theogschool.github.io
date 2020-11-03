# <p align="center"> A Guide to Hosting your Resume Online    

### What is this README?  
This README will explain the details on how I hosted my resume using GitHub Pages and Jekyll and how you can hopefully achieve the same result. I however, would also like to use this README to explain **why** you should use tools like GitHub Pages and Jekyll to host something such as a resume. I will explain this citing Andrew Etter's book: *Modern Technical Writing* My hope is that after reading this you will understand why tools such as these are valuable when performing technical writing today.

### Prerequisites to Hosting your Resume.
While the end goal is to allow you to host a resume online. I will not be elaborating on all the preliminary details. While reading this, I will assume you have access to:

* Basic knowledge of Markdown.
* A Markdown editor of your choice (I went with MarkdownPad)
* A resume formatted in markdown.
* Access to an internet browser of your choice (I used Google Chrome). 

If you are unfamiliar with Markdown I will include a link in the *More Resources* section of this README. I suggest you read it over and develop a resume in Markdown. I will explain why I suggest using Markdown below.

### Hosting your Resume Online:

##### Why Markdown?
Before I explain the formal steps of hosting a resume online. I would first like to explain the reason I have selected the lightweight markup language Markdown over something such as Hypertext Markup Language (HTML). As described by Etter, writing in a language such as Markdown is much more simple and human readable. The actually content in something like HTML might make up only a small percentage of the overall document. So creating a page in Markdown should be simpler overall and be easier if someone wanted to look at your raw documentation.

##### Creating a GitHub account

GitHub is a great resource for hosting something such as a resume online. Hosting a resume online is a great alternative to creating a PDF in something like Microsoft Word. Etter explains, once something is downloaded it will remain there and can become outdated. If you host it online you can make changes to it without needing to send a new copy to someone after each version change. To create a GitHub account:   
1. Search up GitHub with in your internet browser.  
2. Navigate to the sign up page to make an account.

##### Create a GitHub Pages Repository
![Tutorial Gif](gif.gif)
Creating a GitHub Pages repo will allow for distributed version control. Etter explains the advantages of a distributed version controlled system. He explains, everything will stay in sync with the most recent version which I have explained how this is advantageous previously. Etter explains that using a distributed version controlled system such as GitHub Pages has other advantages such as being able to work on your resume offline and being able to document changes made to the resume.  
Creating a GitHub Pages repo can be done in a couple of ways. Personally I created a new repository from scratch. Details on how to achieve this are detailed below.  
1. Click on the green create repository button on the left side of the page.  
2. Enter *name*.github.io under Repository Name where *name* is the username of your GitHub account.  
3. Ensure your repository is set to public and select the add Readme.md button then click **Create Repository** at the bottom of the page.  
4. Click the **add file** button beside the green *code* button and select upload files.  
5. Drag your Resume.md (or whatever you named your resume) file into the box that says "Drag files here..." and click **Commit Changes** at the bottom of the page.  
6. Click on the uploaded resume to view it. As you can see from the gif I posted you may need to edit your resume slightly. More on this in the FAQ's.

##### Formatting the document with Jekyll

Jekyll is a static site generator that can be used to host your resume online. Etter explains many advantages of static sites such as speed, simplicity, portability and security. In this case however, the biggest advantage over a more dynamic website is how easy it is to create. When hosting like a resume, a complex website is not needed. The only functionality needed is for the user to be able to view your resume.  
I used a basic template for Jekyll on GitHub Pages. This should be suffice for the purposes of hosting a resume.  
1. Click the **settings** button above the **add file** I used earlier.  
2. Scroll down until you see the **GitHub Pages** heading.  
3. Click the **choose a theme** button and select the theme you would like to use (I went with minimal).  
4. Click on the text-box beside the name of your repository. Enter index.md.  
5. Type https://name.github.io/resume into your search engine. You should now be able to view your resume.

##### More Resources

[A guide to basic Markdown](https://www.markdowntutorial.com/)  
[*Modern Technical Writing* by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)  
[MarkdownPad](http://markdownpad.com/)

#### Authors and Acknowledgements

Special thanks to Steve Smith (orderedlist) for creating the Jekyll theme *minimal*
Thanks to (Group members here) for reading over and suggesting changes to this readme.

#### FAQs

* **Question: Why is Markdown better than a word processor for creating a resume?**  
Answer: After creating your resume you may wish to update it to better reflect yourself currently as the resume may become outdated. If you use Markdown and host it on a static site generator you can add any new information without the need to send a new copy to whoever has your current resume.

* **Question: After writing my resume in Markdown and uploading it to GitHub why does the formatting get displayed incorrectly?**  
Answer: The Markdown used on GitHub and the Markdown used by default in your Markdown editor might differ slightly. If you are using MarkdownPad try putting a space after each heading.
