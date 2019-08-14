# Flutter Blogger Application
In this project, I will make a open source flutter application for my website & blog (www.walidamriou.com), but I will make it like a framework for make a flutter application for the websites & blogs that based blogger platform. 

### __project license__
GNU Affero General Public License v3.0
about the license: Permissions of this strongest copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights. When a modified version is used to provide a service over a network, the complete source code of the modified version must be made available.
more info here: https://choosealicense.com/licenses/agpl-3.0/

Copyright and license notices must be preserved to: @walidamriou 

### __Notes__
* In this project you need to get "blogger blog id" of you website or blog, to get it:  
1- open your blog dashvoard on blogger.
2- see the url of the page in the location bar.
3- you see like that: 
http://www.blogger.com/blogger.g?blogID=123456789101112#overview/src=dashboard
4- the "blogger blog id" is the "blogID", and in this exemple is: 123456789101112 .

* you need to get "Blogger API key":
1- go to: https://developers.google.com/blogger/docs/3.0/using  .
2- search  "Acquiring and using an API key" in the page.
3- click "Get a Key".
4- in "select or create project", choose  "create a new project".
5- add the project name and wait.
6- the website generate  "Blogger API key".  

* We get the data (posts) by HTTP request, to make the url that use in HTTP request we use: 
https://developers.google.com/blogger/docs/3.0/reference/posts/list#try-it

* we fetch or get the data from the internet (from the blog) by use this method: https://flutter.dev/docs/cookbook/networking/fetch-data  
this method helps us to the data from the url that made it by the method in the last note.

## __version 1__
__Notes about this version__  
* we focuse to develop an app that display just the post text & post info.
* we download the posts in json file & display the titles of the posts in the Home page.
* the title & the info of the post we will put it inside rectange.
* when click on the rectange of a post, the app move to the post of the post.  
__Design__

