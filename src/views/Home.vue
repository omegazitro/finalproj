<template>
  <div class="mt-8">
    <p class="text-3xl text-black text-center m-16 tracking-wider font-thin">
      Welcome, {{ user?.displayName || 'Sponsors' }}!
    </p>
    <img class="h-80 mx-auto" src="../assets/logo2.jpg" alt="Home Image" />
  </div>

  <div class="container mt-8 mx-auto">
    <div class="card lg:card-side bordered">
      <figure>
        <img class="mt-3 ml-4" src="https://picsum.photos/id/1005/400/250" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">LEVEL 1 (One) Charro</h2>
        <p class="font-bold">Grande International Parade - $25,000</p>
        <p>
          <br />
          Name of sponsor on a banner that will start at the Grand International
          Parade, and Ten (10) invitations to Wednesday Night Fiesta Party.
        </p>
        <div class="card-actions">
          <button class="btn btn-success hover:bg-warning">Purchase</button>
          <button class="btn btn-ghost">More info</button>
        </div>
      </div>
    </div>
  </div>

  <div class="container mt-8 mx-auto">
    <div class="card lg:card-side bordered">
      <figure>
        <img class="mt-3 ml-4" src="https://picsum.photos/id/1005/400/250" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">LEVEL 2 (Two) China Poblana</h2>
        <p class="font-bold">Illuminated Parade - $15,000</p>
        <p>
          <br />
          Name of sponsor on a banner that will start the Illuminated Parade,
          and Ten (10) invitations to Wednesday Night Fiesta Party.
        </p>
        <div class="card-actions">
          <button class="btn btn-success hover:bg-warning">Purchase</button>
          <button class="btn btn-ghost">More info</button>
        </div>
      </div>
    </div>
  </div>

  <div class="container mt-8 mx-auto">
    <div class="card lg:card-side bordered">
      <figure>
        <img class="mt-3 ml-4" src="https://picsum.photos/id/1005/400/250" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">LEVEL 3 (Three) Mariachi</h2>
        <p class="font-bold">
          Baile del Sol, Noche Mexicana, or Charro Days Costume Ball- $6,000
        </p>
        <p>
          <br />
          Name of sponsor will be displayed on the grand bandstand during Baile
          del Sol (Sunday, February 18, 2018), or Banner of sponsor displayed at
          the Noche Mexicana or Charro Days Costume Ball venue, and Five (5)
          invitations to Wednesday Night Fiesta Party.
        </p>
        <div class="card-actions">
          <button class="btn btn-success hover:bg-warning">Purchase</button>
          <button class="btn btn-ghost">More info</button>
        </div>
      </div>
    </div>
  </div>

  <div class="container mt-8 mx-auto">
    <div class="card lg:card-side bordered">
      <figure>
        <img class="mt-3 ml-4" src="https://picsum.photos/id/1005/400/250" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">LEVEL 4 (Four) Zarape</h2>
        <p class="font-bold">$5,000</p>
        <p>
          <br />
          Five (5) invitations to Wednesday Night Fiesta Party.
        </p>
        <div class="card-actions">
          <button class="btn btn-success hover:bg-warning">Purchase</button>
          <button class="btn btn-ghost">More info</button>
        </div>
      </div>
    </div>
  </div>

  <div class="container mt-8 mx-auto">
    <div class="card lg:card-side bordered">
      <figure>
        <img class="mt-3 ml-4" src="https://picsum.photos/id/1005/400/250" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">LEVEL 5 (Five) Rebozo</h2>
        <p class="font-bold">$3,000</p>
        <p>
          <br />
          Two (3) invitations to Wednesday Night Fiesta Party.
        </p>
        <div class="card-actions">
          <button class="btn btn-success hover:bg-warning">Purchase</button>
          <button class="btn btn-ghost">More info</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { user } from '../helpers/useAuth'
</script>
