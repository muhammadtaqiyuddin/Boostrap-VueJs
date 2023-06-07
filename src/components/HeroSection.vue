<script setup>
import Button from './Button.vue';
</script>
<template>
  <div class="container py-5">
    <div class="row flex-lg-row-reverse align-items-center d-flex g-5 justify-content-between py-5">
      <div class="col-10 col-sm-8 col-lg-6">
        <lottie-player src="https://assets3.lottiefiles.com/packages/lf20_sk5h1kfn.json" background="transparent" speed="1"
                        style="width: 100%; height: auto;" loop autoplay></lottie-player>
      </div>
      <div class="col-lg-6">
        <h1 class="display-5 fw-bold text-body-emphasis lh-1 mb-3">
          Responsive left <br />
          Aligned hero with image
        </h1>
        <p class="lead">
          Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and
          powerful JavaScript plugins.
        </p>
        <div class="d-grid gap-2 d-md-flex justify-content-md-start">
          <Button text="Primary" class="btn-primary btn-lg px-4 me-md-2" />
          <Button text="Default" class="btn-outline-secondary btn-lg px-4" />
        </div>
      </div>
    </div>
  </div>
</template>