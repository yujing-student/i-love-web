
<script>
    import { CodeBlock } from '@skeletonlabs/skeleton';
    import logo from '$lib/img/try.png';
    import andere from '$lib/img/andere.png';

</script>

<h2 id="week1">week1</h2>
<ul>
    <li>ga naar <a href="#geleerd1">wat heb ik geleerd</a></li>
    <li>ga naar <a href="#gedaan1">wat heb ik gedaan</a></li>
</ul>


<section>

    <h4 id="gedaan1">dit heb ik gedaan</h4>
    <p><strong>2-9</strong>
        ik svelte geinstalleerd en een ontwerp gemaakt van de squadpage
        en
        een tutorial gevolgd van svelte zodat ik beter begrijp wat het is ook weet ik hoe je code meot installerren
    </p>
    <pre><code class="">
                    npm create svelte@latest
                     npm install
                     npm run dev
                    npm install @directus/sdk
                </code></pre>


    <p><strong>3-9</strong>
        Ik heb verder de tutorial gevolgd en
        ik heb gekeken naar hoe ik mijn project kan deployen op vercel en dat is gleukt dankzij deze link <a
                href="https://vercel.com/docs/frameworks/sveltekit">https://vercel.com/docs/frameworks/sveltekit</a>
    </p>


    <p><strong>4-9</strong> ik heb verder de tutorial gevolgd en een schets gemaakt voor mijn profilecard en ik heb op
        vercel deze
        tutorial
        gevonden en dit heeft mij enorm geholpen in het begrijpen van sveltekit
        <a href="https://vercel.com/docs/beginner-sveltekit">https://vercel.com/docs/beginner-sveltekit</a>

        <img src="{logo}">
    </p>



    <p><strong>5-9</strong> ik heb mijn profilecard in code uitgewerkt en het button component gemaakt voor de squad
        page en dit is
        gelukt
        met behulp van de tutorial
        <br>
        <img src="https://raw.githubusercontent.com/yujing-student/i-love-web/main/img.png">

        <br>
        <strong>6-9</strong> ik heb geleerd hoe ik netjes issues kan inschieten en feedback kan geven waardoor
        eerstejaars beter
        begrijpen
        hoe ze naar de oplossing kunnnen werken</p>

    <h3 id="geleerd1">dit heb ik geleerd</h3>


    <h4>svelte</h4>
    <p>dit zijn aantekingen over svelte en sveltekit</p>


    <p>Svelte: Een Compilerende Componentenframework
        Scoped Styling: Elke component heeft zijn eigen CSS-scope, waardoor stijlen niet conflicteren tussen
        componenten.
        <br>
        Reactive State: Veranderingen in data worden automatisch weerspiegeld in de DOM, zonder dat je handmatig
        DOM-manipulatie hoeft te doen.
        <br>
        CSR (Client-Side Rendering): De applicatie wordt volledig in de browser gerenderd, waardoor interactieve
        gebruikerservaringen mogelijk zijn.
        <br>
        Compiler: Svelte compileert je componenten naar efficiënte JavaScript-code, waardoor de runtime overhead
        minimaal
        is.</p>

    <h4>code</h4>
    <p>installeren svelte</p>
    <pre><code class="">
                    npm create svelte@latest
                     npm install
                     npm run dev
                    npm install @directus/sdk
                </code></pre>
    <p>ophalen data uit de databse



    </p>

    <img src="{andere}">


    <h4>sveltekit</h4>
    <p>
        SvelteKit: Een Metaframework Gebouwd op Svelte
        SSG, MPA, AMD, SPA, SSR: SvelteKit ondersteunt verschillende renderingsstrategieën, waaronder Static Site
        Generation
        <br>
        (SSG), Multi-Page Applications (MPA), en Server-Side Rendering (SSR).
        Folder-Based Routing: Je definieert routes door het aanmaken van mappen en bestanden in je projectstructuur.
        Data Fetching: SvelteKit maakt het eenvoudig om data op te halen van servers via GET en POST requests.
        <br>
        Code Splitting: Code wordt slim verdeeld over client en server
    </p>

</section>
