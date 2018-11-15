<template>
  <section class="container">
    <div>
      <logo/>
      <h2 class="subtitle">
        Productos de lona publicitaria reutilizada
      </h2>

      <div>
         <b-embed type="iframe"
                  aspect="16by9"
                  src="https://www.youtube.com/embed/videoseries?list=PLsE_GqJ3pZQ0yJcjPEMExFcyUVxesFHek&loop=1&color=white&controls=0" 
                  frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
                  allowfullscreen>
         </b-embed>
      </div>
      
      
      <ul class="links">
        <li><a
          href="mailto:info@sastradesign.com"
          class="">info@sastradesign.com</a>
        </li>  
        <li><a
          href="https://facebook.com/sastranicaragua"
          target="_blank"
          class="">facebook.com/sastranicaragua</a>
        </li>  
      </ul>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>

.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-family: 'Ink Free Regular';
  font-weight: 300;
  font-size: 25px;
  color: white;
  word-spacing: 5px;
  padding-bottom: 30px;
  padding-top: 30px
}

.links {
  padding-top: 30px;
  font-family: 'Ink Free Regular';
  list-style: none;
  padding-left: 0;
}
.links li{
  padding-bottom: 15px;
}
.links a{
  color: white;
}
</style>
