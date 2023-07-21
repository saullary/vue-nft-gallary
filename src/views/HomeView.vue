<script setup>
import NftList from '../components/nft-list.vue'
</script>

<template>
  <main>
    <header>
      <div class="al-c">
        <img src="img/logo.png" height="45" />
        <h1 class="ml-2 fz-18">My NFT Gallary</h1>
      </div>
    </header>
    <div class="ta-c m-9">
      <h2 class="fz-30 d-ib" style="max-width: 700px">HELLO! Welcome to my NFT Gallary.</h2>
    </div>
    <nft-list></nft-list>
  </main>
</template>

<style>
main {
  max-width: 1100px;
  margin: 0 auto;
  padding: 20px;
}
</style>
