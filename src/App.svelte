<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import kjgLogo from './assets/kjg.jpg'
  import Counter from './lib/Counter.svelte'
import ServiceWorker from './lib/ServiceWorker.svelte'
</script>

<main>
  <div>
    <a href="https://www.facebook.com/KjGGraben1/" target="_blank"> 
      <img src={kjgLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
  </div>
  <h1>Zuprteamz</h1>

  <div class="card">
    <Counter />
  </div>

  <div>
    <ServiceWorker/>
  </div>

  <p>
    Zuprteamz für Zuprleude
  </p>

</main>

<style>
  .logo {
    height: 20em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>