# Instaparse2
 Lab 6 - CodePath iOS 102 (Spring 2023)

#### Required Feature
- [x] Users are able to log out
- [x] Users are able to persist their login credentials on multiple app launches
- [x] Users are able to use the camera to take a photo and upload it to the server (your Parse server)
- [x] Users are not able to see other users’ photos until they upload their own.

      - [ ] Fetch the 10 most recent photos within the last 24 hours from the server.
      - [ ] Of those returned in the response, only show the post if the createdAt property is within 24 hours of the logged in user’s last post. Else, just hide it.
      - [ ] Students have an option to implement a blur view in the project.
      - [ ] For storing when the user last made a post, create a lastPostedDate property in the User object that gets updated whenever the user uploads a photo
