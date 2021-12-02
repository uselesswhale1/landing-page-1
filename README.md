# landing-page
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, shrink-to-fit=no"
    />
    <meta name="description" content="" />
    <meta name="author" content="" />
    <title>Landing page</title>
    <link rel="icon" type="image/x-icon" href="assets/favicon.ico" />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css"
      rel="stylesheet"
      type="text/css"
    />
    <link
      href="https://fonts.googleapis.com/css?family=Lato:300,400,700,300italic,400italic,700italic"
      rel="stylesheet"
      type="text/css"
    />
    <link href="css/styles.css" rel="stylesheet" />
  </head>
  <body>
    <nav class="navbar navbar-light bg-light static-top">
      <div class="container">
        <a class="navbar-brand" href="#!">Brand name</a>
        <a class="btn btn-primary" href="#signup">Sign Up</a>
      </div>
    </nav>

    <header class="masthead">
      <div class="container position-relative">
        <div class="row justify-content-center">
          <div class="col-xl-6">
            <div class="text-center text-white">
              <h1 class="mb-5">
                Generate more leads with a professional landing page!
              </h1>
              <form
                class="form-subscribe"
                id="contactForm"
                data-sb-form-api-token="API_TOKEN"
              >
                <div class="row">
                  <div class="col">
                    <input
                      class="form-control form-control-lg"
                      id="emailAddress"
                      type="email"
                      placeholder="Email Address"
                      data-sb-validations="required,email"
                    />
                    <div
                      class="invalid-feedback text-white"
                      data-sb-feedback="emailAddress:required"
                    >
                      Email Address is required.
                    </div>
                    <div
                      class="invalid-feedback text-white"
                      data-sb-feedback="emailAddress:email"
                    >
                      Email Address Email is not valid.
                    </div>
                  </div>
                  <div class="col-auto">
                    <button
                      class="btn btn-primary btn-lg disabled"
                      id="submitButton"
                      type="submit"
                    >
                      Submit
                    </button>
                  </div>
                </div>

                <div class="d-none" id="submitSuccessMessage">
                  <div class="text-center mb-3">
                    <div class="fw-bolder">Form submission successful!</div>
                    <p>To activate this form, sign up at</p>
                    <a class="text-white" href="#"></a>
                  </div>
                </div>
                <div class="d-none" id="submitErrorMessage">
                  <div class="text-center text-danger mb-3">
                    Error sending message!
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </header>

    <section class="features-icons bg-light text-center">
      <div class="container">
        <div class="row">
          <div class="col-lg-4">
            <a href="">
              <div class="features-icons-item mx-auto mb-5 mb-lg-0 mb-lg-3">
                <div class="features-icons-icon d-flex">
                  <i class="bi-bookmark-star m-auto text-primary"></i>
                </div>
                <h3>Example1</h3>
                <p class="lead mb-0">
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                  Alias, quia quidem.
                </p>
              </div>
            </a>
          </div>
          <div class="col-lg-4">
            <div class="features-icons-item mx-auto mb-5 mb-lg-0 mb-lg-3">
              <div class="features-icons-icon d-flex">
                <i class="bi-bookmark-check m-auto text-primary"></i>
              </div>
              <h3>Example2</h3>
              <p class="lead mb-0">
                Lorem ipsum dolor, sit amet consectetur adipisicing.
              </p>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="features-icons-item mx-auto mb-0 mb-lg-3">
              <div class="features-icons-icon d-flex">
                <i class="bi-bookmark-heart m-auto text-primary"></i>
              </div>
              <h3>Example3</h3>
              <p class="lead mb-0">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quis
                accusantium dicta, iure vel iste, aut
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="showcase">
      <div class="container-fluid p-0">
        <div class="row g-0">
          <div
            class="col-lg-6 order-lg-2 text-white showcase-img"
            style="background-image: url('assets/img/bg-showcase-1.jpg')"
          ></div>
          <div class="col-lg-6 order-lg-1 my-auto showcase-text">
            <h2>New York</h2>
            <p class="lead mb-0">
              the most populous city in the United States. With a 2020
              population of 8,804,190 distributed over 300.46 square miles
              (778.2 km2), New York City is also the most densely populated
              major city in the United States. Located at the southern tip of
              the State of New York, the city is the center of the New York
              metropolitan area, the largest metropolitan area in the world by
              urban area
            </p>
          </div>
        </div>
        <div class="row g-0">
          <div
            class="col-lg-6 text-white showcase-img"
            style="background-image: url('assets/img/bg-showcase-2.jpg')"
          ></div>
          <div class="col-lg-6 my-auto showcase-text">
            <h2>Chicago</h2>
            <p class="lead mb-0">
              Chicago has a pretty strong national reputation for being a very
              clean city. ... Chicago is well known for having a great deal of
              corruption within its political machine, going back nearly 100
              years.
            </p>
          </div>
        </div>
        <div class="row g-0">
          <div
            class="col-lg-6 order-lg-2 text-white showcase-img"
            style="background-image: url('assets/img/bg-showcase-3.jpg')"
          ></div>
          <div class="col-lg-6 order-lg-1 my-auto showcase-text">
            <h2>Los Angeles</h2>
            <p class="lead mb-0">
              LLos Angeles is a sprawling Southern California city and the
              center of the nation’s film and television industry. Near its
              iconic Hollywood sign, studios such as Paramount Pictures,
              Universal and Warner Brothers offer behind-the-scenes tours.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="testimonials text-center bg-light">
      <div class="container">
        <h2 class="mb-5">What people are saying...</h2>
        <div class="row">
          <div class="col-lg-4">
            <div class="testimonial-item mx-auto mb-5 mb-lg-0">
              <img
                class="img-fluid rounded-circle mb-3"
                src="assets/img/testimonials-1.jpg"
                alt="..."
              />
              <h5>Name Surname</h5>
              <p class="font-weight-light mb-0">
                "Tell me and I forget. Teach me and I remember. Involve me and I
                learn."
              </p>
              <ul class="list-inline mb-0">
                <li class="list-inline-item me-4">
                  <a href="#!"><i class="bi-facebook fs-3"></i></a>
                </li>
                <li class="list-inline-item me-4">
                  <a href="#!"><i class="bi-twitter fs-3"></i></a>
                </li>
                <li class="list-inline-item">
                  <a href="#!"><i class="bi-instagram fs-3"></i></a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="testimonial-item mx-auto mb-5 mb-lg-0">
              <img
                class="img-fluid rounded-circle mb-3"
                src="assets/img/testimonials-2.jpg"
                alt="..."
              />
              <h5>Name Surname</h5>
              <p class="font-weight-light mb-0">
                "Many of life's failures are people who did not realize how
                close they were to success when they gave up."
              </p>
              <ul class="list-inline mb-0">
                <li class="list-inline-item me-4">
                  <a href="#!"><i class="bi-facebook fs-3"></i></a>
                </li>
                <li class="list-inline-item me-4">
                  <a href="#!"><i class="bi-twitter fs-3"></i></a>
                </li>
                <li class="list-inline-item">
                  <a href="#!"><i class="bi-instagram fs-3"></i></a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="testimonial-item mx-auto mb-5 mb-lg-0">
              <img
                class="img-fluid rounded-circle mb-3"
                src="assets/img/testimonials-3.jpg"
                alt="..."
              />
              <h5>Name Surname</h5>
              <p class="font-weight-light mb-5 mb-lg-0">
                "Yesterday is history, tomorrow is a mystery, and today is a
                gift... That's why they call it present"
              </p>
              <ul class="list-inline mb-0">
                <li class="list-inline-item me-4">
                  <a href="#!"><i class="bi-facebook fs-3"></i></a>
                </li>
                <li class="list-inline-item me-4">
                  <a href="#!"><i class="bi-twitter fs-3"></i></a>
                </li>
                <li class="list-inline-item">
                  <a href="#!"><i class="bi-instagram fs-3"></i></a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="call-to-action text-white text-center" id="signup">
      <div class="container position-relative">
        <div class="row justify-content-center">
          <div class="col-xl-6">
            <h2 class="mb-4">Ready to get started? Sign up now!</h2>
            <form
              class="form-subscribe"
              id="contactFormFooter"
              data-sb-form-api-token="API_TOKEN"
            >
              <div class="row">
                <div class="col">
                  <input
                    class="form-control form-control-lg"
                    id="emailAddressBelow"
                    type="email"
                    placeholder="Email Address"
                    data-sb-validations="required,email"
                  />
                  <div
                    class="invalid-feedback text-white"
                    data-sb-feedback="emailAddressBelow:required"
                  >
                    Email Address is required.
                  </div>
                  <div
                    class="invalid-feedback text-white"
                    data-sb-feedback="emailAddressBelow:email"
                  >
                    Email Address Email is not valid.
                  </div>
                </div>
                <div class="col-auto">
                  <button
                    class="btn btn-primary btn-lg disabled"
                    id="submitButton"
                    type="submit"
                  >
                    Submit
                  </button>
                </div>
              </div>
              <div class="d-none" id="submitSuccessMessage">
                <div class="text-center mb-3">
                  <div class="fw-bolder">Form submission successful!</div>
                </div>
              </div>

              <div class="d-none" id="submitErrorMessage">
                <div class="text-center text-danger mb-3">
                  Error sending message!
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <footer class="footer bg-light">
      <div class="container">
        <div class="row">
          <div class="col-lg-6 h-100 text-center text-lg-start my-auto">
            <ul class="list-inline mb-2">
              <li class="list-inline-item"><a href="#!">About</a></li>
              <li class="list-inline-item">⋅</li>
              <li class="list-inline-item"><a href="#!">Contact</a></li>
              <li class="list-inline-item">⋅</li>
              <li class="list-inline-item"><a href="#!">Terms of Use</a></li>
              <li class="list-inline-item">⋅</li>
              <li class="list-inline-item"><a href="#!">Privacy Policy</a></li>
            </ul>
            <p class="text-muted small mb-4 mb-lg-0">
              &copy; Your Website 2021. All Rights Reserved.
            </p>
          </div>
          <div class="col-lg-6 h-100 text-center text-lg-end my-auto">
            <ul class="list-inline mb-0">
              <li class="list-inline-item me-4">
                <a href="#!"><i class="bi-facebook fs-3"></i></a>
              </li>
              <li class="list-inline-item me-4">
                <a href="#!"><i class="bi-twitter fs-3"></i></a>
              </li>
              <li class="list-inline-item">
                <a href="#!"><i class="bi-instagram fs-3"></i></a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
    <script src="js/scripts.js"></script>
  </body>
</html>
