# Blog 
This is a personal blog website made on Node.js using Express.js, EJS and MongoDB. The front end is made using HTML, CSS and JavaScript.



## Sample
 

### Homepage

![image](https://user-images.githubusercontent.com/66895829/114231933-bffc6500-9998-11eb-8b36-9b4a1011a18c.png)


### Compose New Post

![image](https://user-images.githubusercontent.com/66895829/114232048-ea4e2280-9998-11eb-900e-204b19321f6a.png)


### View Post

![image](https://user-images.githubusercontent.com/66895829/114232084-f4702100-9998-11eb-95e3-c7bec7b8408a.png)



The final version of the website will not have buttons for composing, updating and deleting a post as that must be a previleged process that can only be done by the admin(owner of blog), not a any user. It will be done using simple URL routing. 

### Example
* To compose a new post, all the admin must do is type "/compose" in front of the root route.
* To delete a post at "www.xyz.com/posts/6070aca4e31c414a109d3dba" URL all the admin has to do is type "/delete" in front of the already existing URL as so "www.xyz.com/posts/6070aca4e31c414a109d3dba/delete".
* To update a post at "www.xyz.com/posts/6070aca4e31c414a109d3dba" URL all the admin has to do is type "/update" in front of the already existing URL as so "www.xyz.com/posts/6070aca4e31c414a109d3dba/update".

The website also has prebuilt About and Contact routes and pages that the admin can edit according to their needs.
