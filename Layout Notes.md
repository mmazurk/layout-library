
# Learning Layouts

## Using Regular CSS

--- 

    display

    height
    width

    margin
    border
    padding

    background-color
    color

    text-align
    line-height

--- 

##  Bootstrap

Centering with Fixed Width

    <div class="mx-auto" style="width: 200px;">
        margin left/right auto
        width must be set manually
    </div>

Max Width or Height of image

    <img class="mw-100" src="..." alt="max width 100%">
    <img class="mH-100" src="..." alt="max height 100%">

Text alignment

    <p class="text-left">Left aligned text on all viewport sizes.</p>
    <p class="text-center">Center aligned text on all viewport sizes.</p>
    <p class="text-right">Right aligned text on all viewport sizes.</p>

Centered Banner, Full Section Below

    <div class="container p-5 my-5 border text-center w-50 bg-dark-subtle">
      <h1>Hello</h1>
      <p>This is some text</p>
    </div>
    <div class="container">
    </div>

Margins and Padding

Adding the *container* class is important because it will automatically center it.

    <div class="container mb-3 w-50 p-3 bg-danger">
        margin bottom 3 rem
        width 50%
        background color info
        padding 3 rem
    </div>

    <div class="container mb-3 w-50 p-3 bg-info">
        margin bottom 3 rem
        width 50%
        background color info
        padding 3 rem
    </div>

    t - top
    b - bottom
    l - left
    r - right
    x - left/right
    y - top/bottom

