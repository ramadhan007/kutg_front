<template>
  <div class="home">
    <!-- Header Section Begin -->
    <Header />
    <HerocaroKutg />
    <BannerKutg />
    <InstaKutg />
    <PartnerKutg />
    <FooterKutg />
    <!-- Header End -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/HeaderKutg.vue";
import HerocaroKutg from "@/components/herocaroKutg.vue";
import BannerKutg from "@/components/BannerKutg.vue";
import InstaKutg from "@/components/InstaKutg.vue";
import PartnerKutg from "@/components/PartnerKutg";
import FooterKutg from "@/components/FooterKutg";
export default {
  name: "Home",
  components: {
    Header,
    HerocaroKutg,
    BannerKutg,
    InstaKutg,
    PartnerKutg,
    FooterKutg,
  },
};
</script>
