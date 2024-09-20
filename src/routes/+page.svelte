<script>
    let name = "Supanile";
    let img = "https://images.unsplash.com/photo-1726664182321-6c8ba2ad912a?q=80&w=1887&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D";
    import About from "./about.svelte";

    const user = {
        name: "Supanile",
        age: 22,
        favLang: "Svelte"
    }
</script>

<About {...user}/>
<img src={img} alt="" style="max-width: 300px; height: auto;">
<p>Create your package using @sveltejs/package and preview/showcase your work with SvelteKit</p>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<style>
    h1 {
        color: red;
    }
    img {
        max-width: 300px;
        height: auto;
    }
</style>