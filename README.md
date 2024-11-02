# project name is My Advanced Blog

## basic structure
1. loading page
2. home page
3. footer

## sections
- header (nav)
- main (artical and aside)
- footer (contact link)

## loading page
this page for use appropriately sized image, non-blocking css loading.
these include:
* spinner-wrapper
* spinner-border

## home page 
this page include 
1. section(header) .
2. section(main) .
3. footer.

## header
this section include nav.
nav contains title , nav-item and navbar-toggler(button).
header is responsive navigation menu.

the following code shows html code of how i did it :
```html
<header class="header card bg-primary container-fluid ">
    <nav class="nav-links navbar-expand-md bg-primary navbar-dark ">
    <div class="container-fluid cont">
        <h1>My Advanced Blog</h1>
        <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
        <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
        <div class="offcanvas-header bg-primary">
            <h5 class="offcanvas-title" id="offcanvasNavbarLabel">My Advanced Blog</h5>
            <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
        </div>
        <div class="offcanvas-body bg-primary">
            <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
            <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">About</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Contact</a>
                </li>
                <li class="nav-item">
                <a class="nav-link" href="#">Portfolio</a>
                </li>
            </ul>
        </div>
        </div>
    </div>
    </nav>
</header>
```

As you can see , the logo is about the navigation links

## main 
this section include appropriate semantic element 
- article
- aside

### article and aside
main section contain first div:
that is div has semantic element such as "article ".
main section contain also "aside"
that to make the container in the side of page.

## addition
I added a "Back to Top" button that appears on scroll

## footer
footer is simple contact form contain four colums.
1. first colum about My Advanced Blog
2. second colum about element of navbar
3. third colum about links
4. four colum about contact

> *"writed by"* ***Shimaa samir***
