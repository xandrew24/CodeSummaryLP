# Live Project
## Introduction
During my Live Project I had the oportunity to work with some amazing people and learn alot from my instructor. Within the 2 week span I managed to spend a lot of time debugging code, cleaning code and adding requested features. The first project I had worked on called Escap-e required me to create a front end layout created with HTMl and styled with CSS. With this specific project, I got a better grasp on how Navbars work and how to position objects better through CSS. With the Cookery Project I contributed to a project that already had progress and had a single area to create using HTML and CSS to show a recipe.
## Table of Contents
- [Escap-e](#escap-e)
- [Cookery](#cookery)
## Escap-e
My task here was to replicate a website based off an image of how it looks using Bootstrap 5, HTMl and CSS. I created a navbar and positioned it in the middle and also added a background image as well as its own logo.
'''html

    <body>
        <div class="container">
            <div class="row">
                <img id="logo" src="./images/escape-logo-transparent.png" class="img-fluid col-8 col-md-4 mx-auto mx-md-0 mt-5 px-0 ">
            </div>
          </div>

      <div class="container">
        <div class="row">
            <h1 class="header-colon">Adventure Awaits</h1> 
          <div class="row">
            <div class="navbar mx-auto my-auto"> 

              <div class="container">
                <ul class="nav justify-content-evenly nav-border col-xxl-12"> 
                      <a class="nav-link" href="#">Hotel</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Flights</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Cruises</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link">Cars</a>
                    </li>
                </ul>
              </div>
          </div>
        </div>
      </div>
    </body>
    
'''
## Cookery
While working on cookery I delt with some div containers and how rows and columns work to position the card i was working on for the featured recipe on this webpage. Im thankful for this project because i really learned alot about positioning.
'''html
<div class="container-fluid">
  <div class="row">
    <div class="col-lg-6 mt-5 mx-auto">
      <h1 id="feature">Featured</h1>
      <div class="row">
        <div class="card">
          <div class="row">
            <div class="col-md-4 img"> 
            </div>
            <div class="col-md-8">
              <div class="card-body p-5">
                <h5 class="card-title">Vegan Ramen</h5>
                <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.
                </p>
                <button type="button" class="btn btn-lg">View Recipe</button>
              </div>
              <div class="row card-footer">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
'''
