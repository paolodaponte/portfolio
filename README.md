# Paolo Da Ponte — Portfolio

Portfolio personale sviluppato con Astro. Codice scritto a mano, nessun template o page builder.

**Live:** [paolodaponte.dev](https://paolodaponte.dev)

## Tech stack

- [Astro](https://astro.build/) — static site generator
- SCSS con metodologia BEM
- [GSAP](https://gsap.com/) + ScrollTrigger per le animazioni
- Content Collections per i case study

## Struttura

```
src/
  components/     Header, Footer
  content/        Case study in Markdown (Content Collections)
  layouts/        Base.astro con SEO e Open Graph
  pages/          Homepage + pagine progetto dinamiche
  styles/         Reset, variabili, tipografia, global
```

## Sviluppo

```bash
npm install
npm run dev       # Dev server su localhost:4321
npm run build     # Build statico in dist/
npm run preview   # Anteprima del build
```

## SEO

- Meta tag dinamici (title, description, canonical) per ogni pagina
- Open Graph e Twitter Card per anteprime social
- Sitemap automatica con @astrojs/sitemap
- robots.txt
