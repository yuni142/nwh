<template>
  <div class="home">
    <HeaderNwh/>
    <HeroNwh/>
    <WomenNwh/>
    <InstaNwh/>
    <PartnerNwh/>
    <FooterNwh/>

  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderNwh from '@/components/HeaderNwh.vue';
import HeroNwh from '@/components/HeroNwh.vue';
import WomenNwh from '@/components/WomenNwh.vue';
import InstaNwh from '@/components/InstaNwh.vue';
import PartnerNwh from '@/components/PartnerNwh.vue';
import FooterNwh from '@/components/FooterNwh.vue';

export default {
  name: 'Home',
  components: {
    HeaderNwh,
    HeroNwh,
    WomenNwh,
    InstaNwh,
    PartnerNwh,
    FooterNwh
  }
}
</script>
