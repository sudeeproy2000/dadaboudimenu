<div align="center">
  
  ![GitHub repo size](https://img.shields.io/github/repo-size/codewithsadee/grilli)
  ![GitHub stars](https://img.shields.io/github/stars/codewithsadee/grilli?style=social)
  ![GitHub forks](https://img.shields.io/github/forks/codewithsadee/grilli?style=social)
[![Twitter Follow](https://img.shields.io/twitter/follow/codewithsadee_?style=social)](https://twitter.com/intent/follow?screen_name=codewithsadee_)
  [![YouTube Video Views](https://img.shields.io/youtube/views/CjVGp5kGHxA?style=social)](https://youtu.be/CjVGp5kGHxA)

  <br />
  <br />

  <h2 align="center">Grilli - Restaurant Website</h2>

Grilli is a fully responsive restaurant website, <br />Responsive for all devices, build using HTML, CSS, and JavaScript.

<a href="https://codewithsadee.github.io/grilli/"><strong>➥ Live Demo</strong></a>

</div>

<br />

### Demo Screeshots

![Grilli Desktop Demo](./readme-images/desktop.png "Desktop Demo")

### Prerequisites

Before you begin, ensure you have met the following requirements:

- [Git](https://git-scm.com/downloads "Download Git") must be installed on your operating system.

### Run Locally

To run **Grilli** locally, run this command on your git bash:

Linux and macOS:

```bash
sudo git clone https://github.com/codewithsadee/grilli.git
```

Windows:

```bash
git clone https://github.com/codewithsadee/grilli.git
```

### Contact

If you want to contact with me you can reach me at [Twitter](https://www.twitter.com/codewithsadee).

### License

[MIT](https://choosealicense.com/licenses/mit/)

//From index.html

<!--
        - #SERVICE
      -->

        <section
          class="section service bg-black-10 text-center"
          aria-label="service"
        >
          <div class="container">
            <p class="section-subtitle label-2">Flavors Of Dada Boudi</p>

            <h2 class="headline-1 section-title">We Offer Top Class Food</h2>

            <p class="section-text">
              We delight in serving delicious Kolkata style Biriyani along with
              traditional Bengali Thali and other Chinese and Tandoor item
            </p>

            <ul class="grid-list">
              <li>
                <div class="service-card">
                  <a href="#" class="has-before hover:shine">
                    <figure
                      class="card-banner img-holder"
                      style="--width: 285; --height: 336"
                    >
                      <img
                        src="./assets/images/service-1.jpg"
                        width="285"
                        height="336"
                        loading="lazy"
                        alt="Breakfast"
                        class="img-cover"
                      />
                    </figure>
                  </a>

                  <div class="card-content">
                    <h3 class="title-4 card-title">
                      <a href="#">Indian</a>
                    </h3>

                    <a href="#" class="btn-text hover-underline label-2"
                      >View Menu</a
                    >
                  </div>
                </div>
              </li>

              <li>
                <div class="service-card">
                  <a href="#" class="has-before hover:shine">
                    <figure
                      class="card-banner img-holder"
                      style="--width: 285; --height: 336"
                    >
                      <img
                        src="./assets/images/service-2.jpg"
                        width="285"
                        height="336"
                        loading="lazy"
                        alt="Appetizers"
                        class="img-cover"
                      />
                    </figure>
                  </a>

                  <div class="card-content">
                    <h3 class="title-4 card-title">
                      <a href="#">Chinese</a>
                    </h3>

                    <a href="#" class="btn-text hover-underline label-2"
                      >View Menu</a
                    >
                  </div>
                </div>
              </li>

              <li>
                <div class="service-card">
                  <a href="#" class="has-before hover:shine">
                    <figure
                      class="card-banner img-holder"
                      style="--width: 285; --height: 336"
                    >
                      <img
                        src="./assets/images/service-3.jpg"
                        width="285"
                        height="336"
                        loading="lazy"
                        alt="Drinks"
                        class="img-cover"
                      />
                    </figure>
                  </a>

                  <div class="card-content">
                    <h3 class="title-4 card-title">
                      <a href="#">Tandoor</a>
                    </h3>

                    <a href="#" class="btn-text hover-underline label-2"
                      >View Menu</a
                    >
                  </div>
                </div>
              </li>
            </ul>

            <img
              src="./assets/images/shape-1.png"
              width="246"
              height="412"
              loading="lazy"
              alt="shape"
              class="shape shape-1 move-anim"
            />
            <img
              src="./assets/images/shape-2.png"
              width="343"
              height="345"
              loading="lazy"
              alt="shape"
              class="shape shape-2 move-anim"
            />
          </div>
        </section>

        <!--
        - #ABOUT
      -->

        <section
          class="section about text-center"
          aria-labelledby="about-label"
          id="about"
        >
          <div class="container">
            <div class="about-content">
              <p class="label-2 section-subtitle" id="about-label">Our Story</p>

              <h2 class="headline-1 section-title">
                Every corner of the wall has it's own story
              </h2>

              <p class="section-text">
                Lorem Ipsum is simply dummy text of the printingand typesetting
                industry lorem Ipsum has been the industrys standard dummy text
                ever since the when an unknown printer took a galley of type and
                scrambled it to make a type specimen book It has survived not
                only five centuries, but also the leap into.
              </p>

              <div class="contact-label">Book Through Call</div>

              <a
                href="tel:+919831318010"
                class="body-1 contact-number hover-underline"
                >+91 9831318010</a
              >

              <a href="#" class="btn btn-primary">
                <span class="text text-1">Read More</span>

                <span class="text text-2" aria-hidden="true">Read More</span>
              </a>
            </div>

            <figure class="about-banner">
              <img
                src="./assets/images/about-banner.jpg"
                width="570"
                height="570"
                loading="lazy"
                alt="about banner"
                class="w-100"
                data-parallax-item
                data-parallax-speed="1"
              />

              <div
                class="abs-img abs-img-1 has-before"
                data-parallax-item
                data-parallax-speed="1.75"
              >
                <img
                  src="./assets/images/about-abs-image.jpg"
                  width="285"
                  height="285"
                  loading="lazy"
                  alt=""
                  class="w-100"
                />
              </div>

              <div class="abs-img abs-img-2 has-before">
                <img
                  src="./assets/images/badge-2.png"
                  width="133"
                  height="134"
                  loading="lazy"
                  alt=""
                />
              </div>
            </figure>

            <img
              src="./assets/images/shape-3.png"
              width="197"
              height="194"
              loading="lazy"
              alt=""
              class="shape"
            />
          </div>
        </section>

        <!--
        - #SPECIAL DISH
      -->

        <section class="special-dish text-center" aria-labelledby="dish-label">
          <div class="special-dish-banner">
            <img
              src="./assets/images/special-dish-banner.jpg"
              width="940"
              height="900"
              loading="lazy"
              alt="special dish"
              class="img-cover"
            />
          </div>

          <div class="special-dish-content bg-black-10">
            <div class="container">
              <img
                src="./assets/images/badge-1.png"
                width="28"
                height="41"
                loading="lazy"
                alt="badge"
                class="abs-img"
              />

              <p class="section-subtitle label-2">Special Dish</p>

              <h2 class="headline-1 section-title">Mutton Biriyani</h2>

              <p class="section-text">
                Kolkata style mutton biriyani is the most significant item of
                Dada Boudi Hotel.
              </p>

              <div class="wrapper">
                <span class="span body-1">₹340.00</span>
              </div>

              <a href="#" class="btn btn-primary">
                <span class="text text-1">View All Menu</span>

                <span class="text text-2" aria-hidden="true"
                  >View All Menu</span
                >
              </a>
            </div>
          </div>

          <img
            src="./assets/images/shape-4.png"
            width="179"
            height="359"
            loading="lazy"
            alt=""
            class="shape shape-1"
          />

          <img
            src="./assets/images/shape-9.png"
            width="351"
            height="462"
            loading="lazy"
            alt=""
            class="shape shape-2"
          />
        </section>
