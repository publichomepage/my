<!-- Projects-->
<section class="projects-section bg-light" id="projects">
    <div class="container px-4 px-lg-5">
        <!-- Featured Project Row-->
        <div class="row gx-0 mb-4 mb-lg-5 align-items-center">
            <div class="col-xl-8 col-lg-7"><img class="img-fluid mb-3 mb-lg-0" src="assets/img/bg-masthead.jpg" alt="..." /></div>
            <div class="col-xl-4 col-lg-5">
                <div class="featured-text text-center text-lg-left">
                    <h4>Who is it designed for ?</h4>
                    <p class="text-black-50 mb-0">Whether you're a professional, celebrity, entrepreneur, or social enthusiast, a public homepage is your gateway to the world. From personal passions to professional ventures, people are building and showcasing their projects with a public homepage!</p>
                </div>
            </div>
        </div>
        <!-- Project One Row-->
        <div class="row gx-0 mb-5 mb-lg-0 justify-content-center">
            <div class="col-lg-6"><img class="img-fluid" src="assets/img/demo-image-01.jpg" alt="..." /></div>
            <div class="col-lg-6">
                <div class="bg-black text-center h-100 project">
                    <div class="d-flex h-100">
                        <div class="project-text w-100 my-auto text-center text-lg-left">
                            <h4 class="text-white">One Page for all</h4>
                            <p class="mb-0 text-white-50">Your connections, videos, articles, any crafts of cart, all in here that users want to see.</p>
                            <hr class="d-none d-lg-block mb-0 ms-0" />
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Project Two Row-->
        <div class="row gx-0 justify-content-center">
            <div class="col-lg-6"><img class="img-fluid" src="assets/img/demo-image-02.jpg" alt="..." /></div>
            <div class="col-lg-6 order-lg-first">
                <div class="bg-black text-center h-100 project">
                    <div class="d-flex h-100">
                        <div class="project-text w-100 my-auto text-center text-lg-right">
                            <h4 class="text-white">Effortless</h4>
                            <p class="mb-0 text-white-50">It's simple to build, integrate and manage ! unlike any other expensive, complex and time consuming platforms!</p>
                            <hr class="d-none d-lg-block mb-0 me-0" />
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
<!-- Signup-->
<section class="signup-section" id="signup">
    <div class="container px-4 px-lg-5">
        <div class="row gx-4 gx-lg-5">
            <div class="col-md-10 col-lg-8 mx-auto text-center">
                <i class="far fa-paper-plane fa-2x mb-2 text-white"></i>
                <h2 class="text-white mb-5">Connect to request your's</h2>
                <!-- to get an API token!-->
                <form class="form-signup" id="contactForm" data-sb-form-api-token="API_TOKEN">
                    <!-- Email address input-->
                    <div class="row input-group-newsletter">
                        <div class="col"><input class="form-control" id="emailAddress" type="email" placeholder="Enter email address..." aria-label="Enter email address..." data-sb-validations="required,email" /></div>
                        <div class="col-auto"><button class="btn btn-primary disabled" id="submitButton" type="Submit" onclick="sendMessage()">Interested</button></div>
                    </div>
                    <div class="invalid-feedback mt-2" data-sb-feedback="emailAddress:required">An email is required.</div>
                    <div class="invalid-feedback mt-2" data-sb-feedback="emailAddress:email">Email is not valid.</div>
                    <!-- Submit success message-->
                    <!---->
                    <!-- This is what your users will see when the form-->
                    <!-- has successfully submitted-->
                    <div class="d-none" id="submitSuccessMessage">
                        <div class="text-center mb-3 mt-2 text-white">
                            <div class="fw-bolder">Thank you for your interest!</div>
                            <br />
                            <a href=""></a>
                        </div>
                    </div>
                    <!-- an error submitting the form-->
                    <div class="d-none" id="submitErrorMessage"><div class="text-center text-danger mb-3 mt-2">Error sending message!</div></div>
                </form>
            </div>
        </div>
    </div>
</section>
