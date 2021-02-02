# Password Protected Github Pages

This is a demo of adding password protection to public github pages. 

It works by creating a md5 hash of the entered password, then the page tries to load content from a folder by that hash. If it can't find it the password was wrong, if it can, it loads the new page fine. 

It also uses cookies to remember you being logged in!

[Check it out](https://stolksdorf.github.io/protected_gh_pages/)
