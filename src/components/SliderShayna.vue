<template>
  <div>
    <!-- Slider Product Section Begin -->
    <section class="women-banner spad">
      <div class="container-fluid">
        <div class="row">
          <div class="col-lg-12 mt-5">
            <div class="section-title"><h2>Popular Product</h2></div>
            <carousel
              class="product-slider"
              :items="4"
              :nav="false"
              :dots="false"
              :responsive="{ 375: { items: 1 }, 720: { items: 4 } }"
            >
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/macbookair.jpg" alt="" />
                  <ul>
                    <li class="w-icon active">
                      <a href="#"><i class="icon_bag_alt"></i></a>
                    </li>
                    <li class="quick-view">
                      <router-link to="/product">+ Quick View</router-link>
                    </li>
                  </ul>
                </div>
                <div class="pi-text">
                  <div class="catagory-name">Mac</div>
                  <router-link to="/product"
                    ><a href="#">
                      <h5>Macbook Air 2020</h5>
                    </a></router-link
                  >
                  <div class="product-price">
                    $14.00
                    <span>$35.00</span>
                  </div>
                </div>
              </div>
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/macbook.jpg" alt="" />
                  <ul>
                    <li class="w-icon active">
                      <a href="#"><i class="icon_bag_alt"></i></a>
                    </li>
                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                  </ul>
                </div>
                <div class="pi-text">
                  <div class="catagory-name">Mac</div>
                  <a href="#">
                    <h5>Macbook Pro 2020</h5>
                  </a>
                  <div class="product-price">$13.00</div>
                </div>
              </div>
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/iphone11.jpg" alt="" />
                  <ul>
                    <li class="w-icon active">
                      <a href="#"><i class="icon_bag_alt"></i></a>
                    </li>
                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                  </ul>
                </div>
                <div class="pi-text">
                  <div class="catagory-name">iPhone</div>
                  <a href="#">
                    <h5>iPhone 11</h5>
                  </a>
                  <div class="product-price">$34.00</div>
                </div>
              </div>
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/iphone11pro.jpg" alt="" />
                  <ul>
                    <li class="w-icon active">
                      <a href="#"><i class="icon_bag_alt"></i></a>
                    </li>
                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                    <li class="w-icon">
                      <a href="#"><i class="fa fa-random"></i></a>
                    </li>
                  </ul>
                </div>
                <div class="pi-text">
                  <div class="catagory-name">iPhone</div>
                  <a href="#">
                    <h5>iPhone 11 Pro</h5>
                  </a>
                  <div class="product-price">$34.00</div>
                </div>
              </div>
              <div class="product-item">
                <div class="pi-pic">
                  <img src="img/iphone x.jpg" alt="" />
                  <ul>
                    <li class="w-icon active">
                      <a href="#"><i class="icon_bag_alt"></i></a>
                    </li>
                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                    <li class="w-icon">
                      <a href="#"><i class="fa fa-random"></i></a>
                    </li>
                  </ul>
                </div>
                <div class="pi-text">
                  <div class="catagory-name">iPhone</div>
                  <a href="#">
                    <h5>iPhone X</h5>
                  </a>
                  <div class="product-price">$34.00</div>
                </div>
              </div>
            </carousel>
          </div>
        </div>
      </div>
    </section>
    <!-- Slider product Section End -->
  </div>
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "SliderShayna",
  components: {
    carousel,
  },
};
</script>

<style scoped>
.product-item {
  margin-right: 25px;
}
</style>