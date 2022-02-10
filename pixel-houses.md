---
layout: page
title: Your Pixel House
description: A collection of 10,000 House NFTS available to purchase
permalink: /pixel-houses
---


  <div class="row mb-5">
    <div class="col-sm">
      <h1 class="title display-1 mb-5">Your Pixel House</h1>
      <h2 class="mb-3">102/10,005 minted</h2>
      <h4 class="mb-5">Your Pixel House is a collection of 10,005 unique houses.</h4>
      <a class="btn btn-info mb-5 mt-3" href="https://opensea.io/collection/your-pixel-house" target="_blank">View on OpenSea</a>
    </div>
    <div class="col-sm">
      <img class="mx-auto d-block" src="/images/pixel-houses-animation.gif" alt="Pixel Houses">
    </div>
  </div>


### Intro
Get your dream Pixel Property while you can. Each house has its own unique properties. Want a garage? Not all of them have one, get a house that has one while you can. Look out for anything Gold, they can be worth a lot! They will be released gradually, check the collection on OpenSea
<a href="Your Pixel House" target="_blank">here</a>.


### How it was built
Similarly to a few other engines out there, it uses layers, like [HashLips Art Engine](https://github.com/HashLips/hashlips_art_engine). However, you may be able to tell that some items are positioned in different places. For example, the windows aren't always in the same place on each house. With the HashLips Art Engine, it positions items in the same place.

How is this done? We create an outline of a house. Then add different colour pixels to indicate if an item should be positioned there or if the area should be filled. A copy is taken of the image to use as a reference, when filling or positioning.

<img src="/images/bungalow.png" width="500" alt="Your Pixel House Bungalow NFT" style="image-rendering: pixelated;">

A green dot means place a window here, with the bottom aligned to it. A purple dot means fill this area with the colour specified in the house colour layer. A flood fill algorithm is used to do this. [NFTPort](https://www.nftport.xyz/) is used to upload the images and json files to IPFS. It is also used for minting.


