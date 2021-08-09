<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Dimpsey Somerset Gin">
    <meta name="author" content="Tommy">
    <title>Dimpsey Somerset Gin</title>

    <!-- Bootstrap core CSS -->
    <link href="../node_modules/bootstrap/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Custom styles for this template -->
    <link href="dimpsey.css" rel="stylesheet">
  </head>
  <body data-bs-spy="scroll" data-bs-target="#main-nav" data-bs-offset="0" tabindex="0">
    
    <header>
      <nav id="main-nav" class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Dimpsey Somerset Gin</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarCollapse">
            <ul class="navbar-nav me-auto mb-2 mb-md-0">
              <li class="nav-item">
                <a class="nav-link" href="#theGin">The Gin</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#whereItsMade">Where it's Made</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>

    <main>

      <div class="animated-illustration">
          <img alt="Dimpsey Somerset Gin illustration" src="./images/main.png" />
      </div>

      <hr class="featurette-divider">

        <div id="theGin" class="container quote">
          <blockquote class="blockquote text-center">
            <p>Distilled in copper pot stills just before Dimpsey - that’s old Somerset for sunset - at the foot of the Mendip Hills, <br />
              using locally foraged botanicals and Cheddar spring water, <br /> this is Somerset Gin.</p>
          </blockquote>
        </div>

        <hr class="featurette-divider">

        <div class="container marketing">

          <div class="row">
            <div class="col-lg-1 thumbnails">

              <label>
                <input type="radio" name="test" value="small" onchange="changeImage('seventy')" checked>
                <img class="thumbnail" alt="70cl bottle of Dimpsey Somerset Gin" src="./images/bottle.png" />
                70cl
              </label>

              <label>
                <input type="radio" name="test" value="big" onchange="changeImage('five')">
                <img class="thumbnail five-cl" alt="5cl bottle of Dimpsey Somerset Gin" src="./images/five.png" />
                5cl
              </label>
            </div><!-- /.col-lg-2 thumbnails -->

            <div class="col-lg-6 main-image">
              <img class="seventy-cl-image" alt="70cl bottle of Dimpsey Somerset Gin" src="./images/bottle.png" />
              <img class="five-cl-image d-none" alt="5cl bottle of Dimpsey Somerset Gin" src="./images/five.png" />
            </div><!-- /.col-lg-6 main-image -->

            <div class="col-lg-5 description">
              <div class="row">
                <div class="col-lg-4">
                  <p><strong>Nose</strong></p>
                  <p>Fragrant juniper, grapefruit & cinnamon</p>
                </div>
                <div class="col-lg-4">
                  <p><strong>Palette</strong></p>
                  <p>Smooth & Full-bodied, balanced with grapefruit and mandarin peel freshness</p>
                </div>
                <div class="col-lg-4">
                  <p><strong>Finish</strong></p>
                  <p>A long extra dry finish, smooth enough to enjoy on the rocks!</p>
                </div>
              </div>

              <p>Our gin comes packaged with a lovely little bag of dried petals that can be used to compliment the organic,
                hand-foraged botanicals that we use. </p>

              <p>Best enjoyed as a gin and tonic. Fill a glass with lots of ice, top with a premium tonic and a curl of pink grapefruit
                or mandarin peel to garnish.</p>

              <form>
                <div class="form-check form-check-inline">
                  <input class="form-check-input" type="radio" name="inlineRadioOptions" id="seventyClRadio" value="seventyCl" onchange="changeImage('seventy')" checked>
                  <label class="form-check-label" for="seventyClRadio"><strong>£35</strong> <small>70cl</small></label>
                </div>
                <div class="form-check form-check-inline">
                  <input class="form-check-input" type="radio" name="inlineRadioOptions" id="fiveClRadio" value="fiveCl" onchange="changeImage('five')">
                  <label class="form-check-label" for="fiveClRadio"><strong>£6</strong> <small>5cl</small></label>
                </div>
              </form>
              <p>Free UK shipping on orders over £50</p>
              <button type="submit" class="btn btn-primary mb-2">ADD TO BASKET</button>
              <button type="submit" class="btn btn-secondary mb-2">BUY NOW</button>
            </div><!-- /.col-lg-4 description -->
          </div><!-- /.row -->
        </div><!-- /.marketing -->

        <div id="whereItsMade" class="container distillery">
          <hr class="featurette-divider">
          <div class="row">

            <div class="col-lg-7 distillery-description">

              <h2 class="featurette-heading">Check out our distillery. <span class="text-muted">It's where the magic happens.</span></h2>
              <p class="lead">Dimpsey Somerset Gin is lovingly hand-crafted in our converted barn, the Still Shed Distillery.</p>

              <p>Our distillery's location is as rural as the taste of our Somerset gin, nested amongst brambles and fields, Dimpsey Somerset Gin is distilled in
                our copper pot stills, using only the finest, locally foraged botanicals - most of which we grow ourselves!</p>

              <p>If you'd like to know more about us or our distillery, check out the Still Shed website!</p>

            </div><!-- /.col-lg-6 distillery-description -->

            <div class="col-lg-5 distillery-image">
              <img alt="The Still Shed Distillery logo" src="./images/stillshed.png" />
            </div>

          </div>

          <hr class="featurette-divider">

        </div><!-- /.distillery -->


      <!-- FOOTER -->
      <footer class="container">
        <p class="float-end"><a href="#">Back to top</a></p>
        <p>&copy; 2021 Still Shed Distillery Limited &middot; <a href="#">Still Shed</a> &middot; <a href="#">Privacy</a></p>
      </footer>
    </main>

    <script src="../node_modules/bootstrap/dist/js/bootstrap.bundle.js"></script>

    <script type="application/javascript">
      function changeImage(size) {
        let element = document.getElementsByClassName(size + "-cl-image")
        element[0].classList.toggle("d-none");

        if (size === "five") {
          document.getElementsByClassName("seventy-cl-image")[0].classList.toggle("d-none");
        } else {
          document.getElementsByClassName("five-cl-image")[0].classList.toggle("d-none");
        }

        document.getElementById(size + "ClRadio").checked = true;
      }
    </script>


  </body>
</html>
