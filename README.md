# bootstrap-cards-shopping-cart
Shopping carts demand intuitive and simple designs that users can quickly comprehend. Using Bootstrap cards, you can implement a layout that meets these demands.

## Tutorial
For detailed instruction's, view Solodev's [How to Create a Contemporary Shopping Cart Layout Using Bootstrap Cards](https://www.solodev.com/blog/web-design/how-to-create-a-contemporary-shopping-cart-layout-using-bootstrap-cards.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/ah28mz59/).

## HTML
The tutorial contains the following basic HTML markup.

```
<div class="row px-5 pt-5">
        <div class="col-md-4 mt-4 mt-sm-0 card-container">
          <div class="card text-center product p-4 pt-5 border-0 h-100 rounded-0">
            <img class="img-fluid d-block mx-auto" src="https://raw.githubusercontent.com/solodev/bootstrap-cards-shopping-cart/master/images/gear-glasses.jpg" alt="Pilot Aviator Glasses Gear Image">
            <div class="card-body p-4 py-0 h-xs-440p">
              <h5 class="card-title font-weight-semi-bold mb-3 w-xl-220p mx-auto">Pilot Aviator Glasses</h5>
              <p class="price">$45.00</p>
            </div>
              <p class="btn w-100 px-4 mx-auto">
                <input type="submit" class="btn btn-dark btn-lg w-100" name="add-button" value="Buy Now">
              </p>
          </div>
        </div>
        
        <div class="col-md-4 mt-4 mt-sm-0 card-container">
          <div class="card text-center product p-4 pt-5 border-0 h-100 rounded-0">
            <img class="img-fluid d-block mx-auto" src="https://raw.githubusercontent.com/solodev/bootstrap-cards-shopping-cart/master/images/gear-hat.jpg" alt="Command Hats Gear Image">
            <div class="card-body p-4 py-0 h-xs-440p">
              <h5 class="card-title font-weight-semi-bold mb-3 w-xl-220p mx-auto">Command Hats</h5>
              <p class="price">$15.00</p>
            </div>
            <p class="btn w-100 px-4 text-center mx-auto">
              <input type="submit" class="btn btn-dark btn-lg w-100" name="add-button" value="Buy Now"></p>
          </div>
        </div>

        <div class="col-md-4 mt-4 mt-sm-0 card-container">
          <div class="card text-center product p-4 pt-5 border-0 h-100 rounded-0">
            <img class="img-fluid d-block mx-auto" src="https://raw.githubusercontent.com/solodev/bootstrap-cards-shopping-cart/master/images/gear-tshirt.jpg" alt="Mission T-Shirts Gear Image">
            <div class="card-body p-4 py-0 h-xs-440p">
              <h5 class="card-title font-weight-semi-bold mb-3 w-xl-220p mx-auto">Mission T-Shirts</h5>
              <p class="price">$25.00</p>
            </div>
            <p class="btn w-100 px-4 mx-auto">
              <input type="submit" class="btn btn-dark btn-lg w-100" name="add-button" value="Buy Now"></p>
          </div>
</div>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```
