<template>
  <div id="app">
    <header class="header">
      <img src="@/assets/img/daos-app.jpg" alt="" class="header__img" />
      <nav class="navbar">
        <div class="container">
          <div class="navbar__inner">
            <ul class="navbar__menu_active" v-if="isActive">
              <li class="navbar__item">
                <a href="#" class="navbar__item-link" @click="isActive = !isActive">Blog</a>
              </li>
              <li class="navbar__item">
                <a href="#" class="navbar__item-link" @click="isActive = !isActive">
                  <i class="icon-twitter"></i>&nbsp;Twitter</a>
              </li>
              <li class="navbar__item">
                <a href="#" class="navbar__item-link" @click="isActive = !isActive">
                  <i class="icon-discord"></i>&nbsp;Discord</a>
              </li>
              <li class="navbar__item">
                <button href="#" class="navbar__item-btn btn-active" @click="isActive = !isActive">
                  Open App
                </button>
              </li>
            </ul>
            <a href="#" class="navbar__logo">Logo</a>
            <button class="navbar__burger" :class="{ navbar__burger_active: isActive }" @click="isActive = !isActive">
              <span></span>
              <span></span>
              <span></span>
            </button>
            <ul class="navbar__menu">
              <li class="navbar__item">
                <a href="#" class="navbar__item-link">Blog</a>
              </li>
              <li class="navbar__item">
                <a href="#" class="navbar__item-link">
                  <i class="icon-twitter"></i>&nbsp;Twitter</a>
              </li>
              <li class="navbar__item">
                <a href="#" class="navbar__item-link">
                  <i class="icon-discord"></i>&nbsp;Discord</a>
              </li>
              <li class="navbar__item">
                <button href="#" class="navbar__item-btn btn-active hover-btn">
                  Open App
                </button>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <div class="container">
        <div class="header__inner">
          <h1 class="header__title">PaymentOS for DAOs</h1>
          <p class="header__description">
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry.
          </p>
          <div class="header__control">
            <button href="#" class="header__control-btn btn-active hover-btn">
              Open App&nbsp;<i class="icon-arrow-link"></i>
            </button>

            <button href="#" class="header__control-btn btn hover-btn">
              Watch Demo
            </button>
          </div>
          <p class="header__results-title">Lorem Ipsum is simply dummy</p>
          <div class="header__results">
            <div class="header__results-item">
              <p class="header__results-num">200+</p>
              <p class="header__results-info">DAO’S</p>
            </div>
            <div class="header__results-item">
              <p class="header__results-num">$35M+</p>
              <p class="header__results-info">DISBURSED</p>
            </div>
            <div class="header__results-item">
              <p class="header__results-num">2500+</p>
              <p class="header__results-info">CONTRIBUTORS</p>
            </div>
          </div>
        </div>
      </div>
    </header>
    <section class="special">
      <div class="container">
        <div class="special__items">
          <div class="special__item-main">
            <h1 class="special__item-main-title">What makes us special 🔥</h1>
            <p class="special__item-main-description">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.
            </p>
          </div>
          <div class="special__item">
            <div class="special__item-ico">
              <i class="icon-step1"></i>
            </div>
            <h6 class="special__item-title">Step 1</h6>
            <p class="special__item-description">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.
            </p>
          </div>
          <div class="special__item">
            <div class="special__item-ico">
              <i class="icon-step2"></i>
            </div>
            <h6 class="special__item-title">Step 2</h6>
            <p class="special__item-description">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.
            </p>
          </div>
          <div class="special__item">
            <div class="special__item-ico">
              <i class="icon-step3"></i>
            </div>
            <h6 class="special__item-title">Step 3</h6>
            <p class="special__item-description">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.
            </p>
          </div>
          <div class="special__item">
            <div class="special__item-ico">
              <i class="icon-step4"></i>
            </div>
            <h6 class="special__item-title">Step 4</h6>
            <p class="special__item-description">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.
            </p>
          </div>
          <div class="special__item">
            <div class="special__item-ico">
              <i class="icon-step5"></i>
            </div>
            <h6 class="special__item-title">Step 5</h6>
            <p class="special__item-description">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="company">
      <div class="container">
        <h2 class="company__title">Trusted by DAOs around the world</h2>
        <div class="company__items">
          <div class="company__item">
            <img src="@/assets/img/Bankless.jpg" alt="" class="company__item-img" />
            <p class="company__item-title">Bankless DAO</p>
          </div>
          <div class="company__item">
            <img src="@/assets/img/Bankless.jpg" alt="" class="company__item-img" />
            <p class="company__item-title">Index Coop</p>
          </div>
          <div class="company__item">
            <img src="@/assets/img/Aave Grants.jpg" alt="" class="company__item-img" />
            <p class="company__item-title">Compund Grants</p>
          </div>
          <div class="company__item">
            <img src="@/assets/img/Olympus.jpg" alt="" class="company__item-img" />
            <p class="company__item-title">Aave Grants DAO</p>
          </div>
          <div class="company__item">
            <img src="@/assets/img/forefront.jpg" alt="" class="company__item-img" />
            <p class="company__item-title">Audio Grants Committee</p>
          </div>
          <div class="company__item">
            <img src="@/assets/img/forefront.jpg" alt="" class="company__item-img" />
            <p class="company__item-title">Olympus DAO</p>
          </div>
          <div class="company__item">
            <img src="@/assets/img/Bankless.jpg" alt="" class="company__item-img" />
            <p class="company__item-title">Party DAO</p>
          </div>
          <div class="company__item">
            <img src="@/assets/img/Aave Grants.jpg" alt="" class="company__item-img" />
            <p class="company__item-title">Olympus DAO</p>
          </div>
          <div class="company__item">
            <img src="@/assets/img/forefront.jpg" alt="" class="company__item-img" />
            <p class="company__item-title">Forefront</p>
          </div>
        </div>
      </div>
    </section>
    <section class="team">
      <div class="container">
        <h2 class="team__title">We are Backed By</h2>
        <p class="team__description">
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry.
        </p>
        <div class="team__items">
          <div class="team__item" v-for="item in team" :key="item.name">
            <img :src="require('@/assets/img/' + item.img)" alt="" class="team__item-img" />
            <h6 class="team__item-title">{{ item.name }}</h6>
            <a href="#" class="team__item-link">
              <i class="team__item-ico team__item-twitter-ico" :class="item.media.twitter">
              </i>
            </a>
            <a href="#" class="team__item-link">
              <i class="team__item-ico" :class="item.media.youtube"> </i>
            </a>
          </div>
        </div>
      </div>
    </section>
    <footer class="footer">
      <div class="container">
        <div class="footer__inner">
          <div class="footer__info">
            <div class="footer__info-header">
              <a href="#" class="footer__info__logo">Logo</a>
              <div class="footer__info__description">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry.
              </div>
              <p class="footer__info-copyright">
                Lorem Ipsum is simply 2022 Inc.
              </p>
            </div>
          </div>
          <div class="footer__media">
            <h6 class="footer__media-title">Subscribe to our newsletter</h6>
            <form action="submit" class="footer__form" @submit.prevent="">
              <div class="footer__form-controls">
                <input type="text" class="footer__form-inp" placeholder="Email" />
                <div class="footer__form__btn-wrapper">
                  <button class="footer__form-btn hover-btn">
                    <i class="icon-arrow-btn"></i>
                  </button>
                </div>
              </div>
              <h6 class="footer__form-description">
                We will send you updates on the latest news and features. No
                spam.
              </h6>
            </form>
            <div class="footer__media-social">
              <div class="footer__media-social-item">
                <i class="icon-youtube"></i>
              </div>
              <div class="footer__media-social-item">
                <i class="icon-discord"></i>
              </div>
              <div class="footer__media-social-item">
                <i class="icon-twitter"></i>
              </div>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isActive: false,
      team: [
        {
          img: "user-1.png",
          name: "Dragonfly Capital",
          media: {
            twitter: "icon-twitter",
            youtube: "icon-youtube",
          },
        },
        {
          img: "user-2.png",
          name: "Leighton Cusack",
          media: {
            twitter: "icon-twitter",
            youtube: "icon-youtube",
          },
        },
        {
          img: "user-3.png",
          name: "Linda Xie",
          media: {
            twitter: "icon-twitter",
            youtube: "icon-youtube",
          },
        },
        {
          img: "user-4.png",
          name: "Sandeep Nailwal",
          media: {
            twitter: "icon-twitter",
            youtube: "icon-youtube",
          },
        },
        {
          img: "user-1.png",
          name: "Cooper Turley",
          media: {
            twitter: "icon-twitter",
            youtube: "icon-youtube",
          },
        },
        {
          img: "user-2.png",
          name: "Consensys",
          media: {
            twitter: "icon-twitter",
            youtube: "icon-youtube",
          },
        },
        {
          img: "user-3.png",
          name: "Ryan Sean Adams",
          media: {
            twitter: "icon-twitter",
            youtube: "icon-youtube",
          },
        },
        {
          img: "user-4.png",
          name: "Mike Dudas",
          media: {
            twitter: "icon-twitter",
            youtube: "icon-youtube",
          },
        },
      ],
    };
  },
};
</script>

<style lang="scss">
.header {
  position: relative;
  width: 100%;
}

.header__img {
  background-image: url("@/assets/img/daos-app.jpg");
  background-repeat: no-repeat;
  background-size: contain;
  position: absolute;
  z-index: -1;
  right: 0;
  bottom: -100px;
}

.header__inner {
  position: relative;
  min-height: 824px;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
}

.navbar {
  position: fixed;
  z-index: 999;
  top: 0;
  left: 0;
  padding: 16px 0;
  width: 100%;
  background: #fff;
  -webkit-box-shadow: 5px 5px 5px -5px rgba(34, 60, 80, 0.6);
  -moz-box-shadow: 5px 5px 5px -5px rgba(34, 60, 80, 0.6);
  box-shadow: 5px 5px 5px -5px rgba(34, 60, 80, 0.6);
}

.navbar__inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.navbar__logo {
  font-size: 1.125rem;
  font-weight: 700;
  font-style: normal;
  line-height: 1.125rem;
  color: #000000;
}

.navbar__menu {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.navbar__item {
  margin-left: 3.125rem;
}

.navbar__item-link {
  font-size: 0.875rem;
  line-height: 0.875rem;
  color: #5e5c6c;
  display: flex;
  align-items: center;
}

.navbar__item-link .icon-twitter {
  font-style: 1.125rem;
}

.btn {
  background: #c5c6c8;
  font-size: 0.875rem;
  line-height: 0.875rem;
  color: #ffffff;
  padding: 0.8125rem 1.25rem;
  border: none;
  border-radius: 0.25rem;
}

.btn-active {
  background: #2962ef;
  font-size: 0.875rem;
  line-height: 0.875rem;
  color: #ffffff;
  padding: 0.8125rem 1.25rem;
  border: none;
  border-radius: 0.25rem;
}

.header__title {
  font-weight: 900;
  font-size: 3rem;
  line-height: 3.875rem;
  color: #232427;
}

.header__description {
  margin-top: 15px;
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 0.875rem;
  line-height: 1.5rem;
  color: #9998a4;
}

.header__control {
  margin-top: 62px;
  display: flex;
}

.header__control-btn {
  margin-right: 1.1875rem;
}

.header__control-btn .icon-arrow-link {
  font-size: 0.625rem;
}

.header__results-title {
  margin-top: 130px;
  font-size: 0.875rem;
  line-height: 1.5rem;
  text-transform: uppercase;
  color: #9998a4;
}

.header__results {
  margin: 25px 0 196px;
  display: flex;
  width: 100%;
}

.header__results-item {
  margin-right: 5rem;
}

.header__results-num {
  font-size: 2.25rem;
  line-height: 2.25rem;
  color: #232427;
  text-transform: uppercase;
}

.header__results-info {
  font-size: 0.875rem;
  line-height: 0.875rem;
  text-transform: uppercase;
  color: #5e5c6c;
}

.special__items {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.special__item {
  max-width: 320px;
  background: #e4eaf4;
  border-radius: 0.5rem;
  padding: 3.75rem 2.5rem 4rem;
  margin-bottom: 3.125rem;
}

.special__item-main {
  max-width: 320px;
  padding: 6.188rem 0 6.375rem;
}

.special__item-main-title {
  font-weight: 700;
  font-size: 2.25rem;
  line-height: 2.75rem;
  color: #232427;
}

.special__item-main-description {
  margin-top: 0.938rem;
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 1.5rem;
  color: #9998a4;
}

.special__item-ico {
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  font-size: 34px;
  width: 60px;
  height: 60px;
  background: #ffffff;
  box-shadow: 0px 6px 15px rgba(35, 36, 39, 0.05);
}

.special__item-title {
  margin-top: 2.5rem;
  font-weight: 700;
  font-size: 1.125rem;
  line-height: 1.125rem;
  color: #232427;
}

.special__item-description {
  margin-top: 1rem;
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 1.5rem;
  color: #9998a4;
}

.company {
  background: #faf9fa;
}

.company__title {
  padding-top: 50px;
  text-align: center;
  font-weight: 700;
  font-size: 1.75rem;
  line-height: 1.75rem;
  color: #232427;
}

.company__items {
  padding: 50px 0;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 4.3rem;
}

.company__item {
  display: flex;
  align-items: center;
}

.company__item-img {
  margin-right: 0.79rem;
}

.company__item-title {
  font-weight: 600;
  font-size: 0.875rem;
  line-height: 0.875rem;
  color: #232427;
}

.team {
  margin-top: 142px;
}

.team__title {
  font-weight: 700;
  font-size: 2.25rem;
  line-height: 2.75rem;
  color: #232427;
}

.team__description {
  margin-top: 1rem;

  font-weight: 400;
  font-size: 0.875rem;
  line-height: 0.875rem;
  color: #5e5c6c;
}

.team__items {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.team__item {
  margin-top: 2.81rem;
  background: #f3f3f3;
  box-shadow: 0px 4px 144px rgba(0, 0, 0, 0.04);
  border-radius: 4px;
  padding: 20px;
  margin-bottom: 20px;
}

.team__item-img {
  width: 215px;
  height: 122px;
}

.team__item-title {
  margin-top: 15px;
  font-weight: 700;
  font-size: 1rem;
  line-height: 1rem;
  color: #232427;
}

.team__item-ico {
  margin-top: 10px;
  font-size: 12px;
}

.team__item-twitter-ico {
  margin-right: 10px;
}

.footer {
  width: 100%;
  margin-top: 122px;
  padding: 97px 0;
  background: #232427;
}

.footer__inner {
  display: flex;
  justify-content: space-between;
}

.footer__info {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.footer__info__logo {
  font-weight: 700;
  font-size: 1.125rem;
  line-height: 1.125rem;
  color: #ffffff;
}

.footer__info__description {
  max-width: 21.7rem;
  margin-top: 1.25rem;
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 1.5rem;
  color: #ffffff;
}

.footer__info-copyright {
  margin-top: 96px;
  max-width: 10.5rem;
  font-weight: 400;
  font-size: 1.125rem;
  line-height: 1.125rem;
  color: #d6d5df;
}

.footer__media-title {
  font-weight: 700;
  font-size: 1rem;
  line-height: 1rem;
  color: #ffffff;
}

.footer__form-controls {
  margin-top: 12px;
  display: flex;
  align-items: center;
}

.footer__form-inp {
  width: 296px;
  height: 56px;
  padding-left: 10px;
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 0.875rem;
  color: #9998a4;
  background: #ffffff;
  border: none;
  border-top-left-radius: 4px;
  border-bottom-left-radius: 4px;
}

.footer__form__btn-wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 56px;
  height: 56px;
  background: #ffffff;
  border-top-right-radius: 4px;
  border-bottom-right-radius: 4px;
}

.footer__form-btn {
  display: flex;
  justify-content: center;
  align-items: center;
  border: none;
  width: 40px;
  height: 40px;
  background: #2962ef;
  border-radius: 4px;
  font-size: 16px;
}

.footer__form-description {
  margin-top: 10px;
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 1.5rem;
  color: #ffffff;
}

.footer__media-social {
  margin-top: 32px;
  display: flex;
}

.footer__media-social-item {
  margin-right: 30px;
  font-size: 24px;
  width: 50px;
  height: 50px;
  background: #5e5c6c;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #ffffff;
}

.footer__media-social-item {
  cursor: pointer;
}

.footer__media-social-item .icon-youtube:before {
  color: #ffffff;
}

.footer__media-social-item:hover .icon-youtube:before {
  color: #ff3c3c;
}

.footer__media-social-item .icon-discord:before {
  color: #ffffff;
}

.footer__media-social-item:hover .icon-discord:before {
  color: #5865f2;
}

.footer__media-social-item .icon-twitter:before {
  color: #ffffff;
}

.footer__media-social-item:hover .icon-twitter:before {
  color: rgb(29, 155, 240);
}

.navbar__burger,
.navbar__menu_active {
  display: none;
}

@media (max-width: 1399px) {
  /* CSS для ширины от 1199px до 1399px */
}

@media (max-width: 1199px) {
  /* CSS для ширины от 992px до 1199px */

  .header__results-title {
    color: #000;
  }

  .special__items {
    justify-content: space-evenly;
  }

  .team__items {
    justify-content: space-evenly;
  }
}

/* md-размер (<=991px) */
@media (max-width: 991px) {
  /* CSS для ширины от 768px до 991px */

  .team__title {
    text-align: center;
  }

  .team__description {
    text-align: center;
  }

  .team__items {
    justify-content: space-evenly;
  }
}

/* sm-размер (<=768px) */
@media (max-width: 767px) {

  /* CSS для ширины от 576px до 767px */
  html,
  body {
    font-size: 14px !important;
  }

  .header__img {
    width: 75%;
  }

  .header__inner {
    min-height: 550px;
  }

  .header__title,
  .header__description,
  .header__results-title {
    text-align: center;
  }

  .header__control,
  .header__results {
    justify-content: center;
  }

  .header__results {
    margin-bottom: 10px;
  }

  .special__items {
    justify-content: center;
  }

  .footer__inner {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .footer__info-header {
    display: none;
  }

  .footer {
    padding: 50px 0;
  }

  .footer__media-social {
    justify-content: center;
  }
}

/* xs-размер (<=575px) */
@media (max-width: 575px) {

  /* CSS для ширины до 575px (включительно) */
  .header__img {
    display: none;
  }

  .navbar__menu,
  .navbar__logo {
    display: none;
  }

  .header__inner {
    min-height: 600px;
  }

  .navbar {
    background: #fff;
    width: 100%;
    padding: 20px 0;
    -webkit-box-shadow: 5px 5px 5px -5px rgba(34, 60, 80, 0.6);
    -moz-box-shadow: 5px 5px 5px -5px rgba(34, 60, 80, 0.6);
    box-shadow: 5px 5px 5px -5px rgba(34, 60, 80, 0.6);
  }

  .navbar__menu_active {
    position: absolute;
    top: 0;
    right: 0;
    background: #fff;
    width: 100%;
    min-height: 80vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-evenly;
    -webkit-box-shadow: 5px 5px 5px -5px rgba(34, 60, 80, 0.6);
    -moz-box-shadow: 5px 5px 5px -5px rgba(34, 60, 80, 0.6);
    box-shadow: 5px 5px 5px -5px rgba(34, 60, 80, 0.6);
  }

  .navbar__menu_active .navbar__item-link,
  .navbar__menu_active .navbar__item-btn {
    font-size: 24px;
  }

  .navbar__burger {
    margin-left: 90%;
    display: block;
    width: 30px;
    height: 20px;
    position: relative;
    border: none;
    background: none;
  }

  .navbar__burger span {
    position: absolute;
    right: 0;
    top: 0;
    display: block;
    width: 100%;
    height: 2px;
    background: #000;
    transition: all 0.08s ease-in;
  }

  .navbar__burger span:nth-child(1) {
    top: 0;
  }

  .navbar__burger span:nth-child(2) {
    top: 50%;
    transform: translateY(-50%);
  }

  .navbar__burger span:nth-child(3) {
    top: 100%;
  }

  .navbar__burger_active span:nth-child(1) {
    top: 50%;
    transform: rotate(45deg);
  }

  .navbar__burger_active span:nth-child(2) {
    display: none;
  }

  .navbar__burger_active span:nth-child(3) {
    top: 50%;
    transform: rotate(-45deg);
  }

  .header__results-num {
    font-size: 32px;
  }

  .header__results-item {
    margin-right: 20px;
    text-align: center;
  }
}
</style>
