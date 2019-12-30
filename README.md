# input-fields-with-fontawesome
Adding icons to your input fields (such as login or registration forms) gives the form a touch of personality and helps break up otherwise plain input fields.

## Tutorial
For detailed instruction's, view Solodev's [How to Add Font Awesome Icons to Your Input Fields](https://www.solodev.com/blog/web-design/how-to-add-font-awesome-icons-to-your-input-fields.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/ocq126fm/).

## HTML
The tutorial contains the following basic HTML markup.

```
 <section class="container min-container py-md-5 mt-4">
        <div class="card-panel p-sm-5 position-relative">
            <div class="text-center">
                <img src="https://raw.githubusercontent.com/solodev/input-fields-with-fontawesome/master/images/lunar-xp-logo.png" alt="Logo" class="img-fluid w-50">
                <h1 class="h2 mt-5">Welcome, Explorer!</h1>
            </div>
            <form id="loginForm" class="mt-5">
                  <p class="small mb-2 text-scarlet"></p>
              <div class="form-group position-relative">
                <label for="email" class="sr-only">Email</label>
                <input class="form-control input-lg rounded-0" id="email" name="email" type="text" placeholder="Email / Username" required="">
                <i class="fa fa-user fa-lg position-absolute"></i>
              <span style="opacity: 1; left: 502px; top: 14.5px; width: 19px; min-width: 19px; height: 13px; position: absolute;"></span></div>
              <label for="password" class="pull-left sr-only">Password</label>
              <div class="position-relative">
                <input class="form-control input-lg rounded-0" id="password" name="password" type="password" placeholder="Password" required="">
                <i class="fa fa-lock fa-lg position-absolute"></i>
              <span style="opacity: 1; left: 502px; top: 14.5px; width: 19px; min-width: 19px; height: 13px; position: absolute;"></span></div>
              <div class="text-center my-4">
                <button class="btn btn-primary text-white btn-lg text-uppercase" type="submit">Log in</button>
              </div>
            </form>
            </div>
          </div>      
 </section>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
```