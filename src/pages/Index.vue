<template>
  <Layout>
    <img class="greet-image" src="../../uploads/Landscapes/Hilltops near Sintra.jpg" />

    <h2 class="mb-4">Welcome!</h2>
    <p>
      This is the website for the art of Tom Greenwood. 
    </p>


    <h3 class="mt-5 mb-4">Living artsits I like</h3>
    <ul>
      <li>
        <a target="_blank" rel="noopener" href="https://www.luca.indraccolo.com/"> Luca Indracollo</a> Taught me.
      </li>
      <li>
        <a target="_blank" rel="noopener" href="https://sjfuerst.com/"> Sally Jane Fuerst</a> 
      </li>
      <li>
        <a target="_blank" rel="noopener" href="https://lot5collective.com/"> Lot 5 collective</a>   
      </li>
      <li>
        <a target="_blank" rel="noopener" href="https://www.industryworkshops.co.uk/"> Industry Workshops</a>  
      </li>
    </ul>

    <h3 class="mt-5 mb-4">My site</h3>
    <p>I built this site using <a href="https://gridsome.org/starters/bootstrap-starter/">A starter template</a> by <a href="https://lohe.dev"> Loke Carlsson</a> .
       It is deployed via  <a href="https://www.netlify.com/">Netlify</a> . If you're interested to build one yourself (it's ALL FREE) just click on the 
       starter template link above and follow the intructions (and email me if you get stuck).
    </p>

    
    

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Tom's art site"
  }
}
</script>

<style>
.greet-image {
  display: block;
  margin: auto;
  width: 90%;
  max-width: 500px;
  padding-bottom: 50px;
}
</style>
