<template>
  <div class="column">
    <div class="card">
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="http://bulma.io/images/placeholders/1280x960.png" alt="Image">
        </figure>
      </div>
      <div class="card-content">
        <div class="columns">
          <user></user>
        </div>

        <div class="content">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          Phasellus nec iaculis mauris. <a>@bulmaio</a>.
          <a>#css</a> <a>#responsive</a>
          <br>
          <small>11:09 PM - 1 Jan 2016</small>
        </div>
      </div>
      <div class="card-footer">
        <div class="card-footer-item"><button class="button is-fullwidth">Like</button></div>
        <div class="card-footer-item"><button class="button is-fullwidth">Share</button></div>
        <div class="card-footer-item"><button class="button is-fullwidth">Details</button></div>
      </div>
    </div>
  </div>
</template>
<script>
  import User from '@/Community/User';

  export default{
    components: {
      User,
    },
  };
</script>
