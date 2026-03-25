<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Founji — Creative Studio | Design & Digital à Lévis, QC</title>
    <meta name="description" content="Founji est un studio de création graphique & digital basé à Lévis, QC. Design, UI/UX, Motion, Web et Publicité.">
    <meta name="author" content="Youssef Founji">
    <meta property="og:title" content="Founji — Creative Studio">
    <meta property="og:description" content="Studio de création graphique & digital — Lévis, QC">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://founji.com">
    <link rel="canonical" href="https://founji.com">

    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;500;600;700;800&family=Outfit:wght@300;400;500;600&display=swap" rel="stylesheet">

    <!-- GSAP + ScrollTrigger + Lenis CDN -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js"></script>
    <script src="https://unpkg.com/lenis@1.1.18/dist/lenis.min.js"></script>

    <style>
    /* ═══════════════════════════════════════════ */
    /*  CSS VARIABLES                              */
    /* ═══════════════════════════════════════════ */
    :root {
        --bg: #0a0a0a;
        --bg-alt: #111111;
        --text: #f0f0f0;
        --accent: #c8ff00;
        --gray: #888888;
        --gray-light: #555555;
        --border: rgba(255,255,255,0.08);
        --font-heading: 'Syne', sans-serif;
        --font-body: 'Outfit', sans-serif;
        --ease-expo: cubic-bezier(0.22, 1, 0.36, 1);
        --ease-smooth: cubic-bezier(0.16, 1, 0.3, 1);
    }

    /* ═══════════════════════════════════════════ */
    /*  RESET & BASE                               */
    /* ═══════════════════════════════════════════ */
    *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

    html {
        font-size: 16px;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
    }
    html.lenis, html.lenis body { height: auto; }
    .lenis.lenis-smooth { scroll-behavior: auto !important; }

    body {
        background: var(--bg);
        color: var(--text);
        font-family: var(--font-body);
        font-weight: 400;
        line-height: 1.6;
        overflow-x: hidden;
        cursor: none;
    }

    a { color: inherit; text-decoration: none; cursor: none; }
    img { display: block; max-width: 100%; }
    button { border: none; background: none; color: inherit; font-family: inherit; cursor: none; }

    ::selection {
        background: var(--accent);
        color: var(--bg);
    }

    /* ═══════════════════════════════════════════ */
    /*  GRAIN / NOISE OVERLAY                      */
    /* ═══════════════════════════════════════════ */
    .grain {
        position: fixed; inset: -200%; width: 400%; height: 400%;
        z-index: 10000; pointer-events: none; opacity: 0.03;
        background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.7' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='1'/%3E%3C/svg%3E");
        background-size: 200px 200px;
        animation: grainShift 0.5s steps(1) infinite;
    }
    @keyframes grainShift {
        0%   { transform: translate(0, 0); }
        25%  { transform: translate(-5%, -10%); }
        50%  { transform: translate(7%, -15%); }
        75%  { transform: translate(-8%, 5%); }
        100% { transform: translate(3%, 10%); }
    }

    /* ═══════════════════════════════════════════ */
    /*  CUSTOM CURSOR                              */
    /* ═══════════════════════════════════════════ */
    .cursor {
        position: fixed; width: 12px; height: 12px;
        background: var(--text); border-radius: 50%;
        pointer-events: none; z-index: 10001;
        mix-blend-mode: difference;
        transform: translate(-50%, -50%);
        transition: width 0.35s var(--ease-expo), height 0.35s var(--ease-expo);
        left: -50px; top: -50px;
    }
    .cursor.is-hover { width: 50px; height: 50px; }
    .cursor.is-accent { background: var(--accent); mix-blend-mode: normal; }

    @media (pointer: coarse) {
        .cursor { display: none !important; }
        body, a, button { cursor: auto; }
    }

    /* ═══════════════════════════════════════════ */
    /*  PRELOADER                                  */
    /* ═══════════════════════════════════════════ */
    .preloader {
        position: fixed; inset: 0; z-index: 9999;
        background: var(--bg);
        display: flex; flex-direction: column;
        align-items: center; justify-content: center;
        gap: 1rem;
    }
    .preloader__logo {
        font-family: var(--font-heading);
        font-size: clamp(2rem, 5vw, 3.5rem);
        font-weight: 800; letter-spacing: -0.03em;
        opacity: 0; transform: translateY(15px);
    }
    .preloader__logo span { color: var(--accent); }
    .preloader__bar {
        width: 60px; height: 2px;
        background: rgba(255,255,255,0.1);
        border-radius: 2px; overflow: hidden;
    }
    .preloader__bar-fill {
        width: 0%; height: 100%;
        background: var(--accent);
        border-radius: 2px;
    }

    /* ═══════════════════════════════════════════ */
    /*  NAVBAR                                     */
    /* ═══════════════════════════════════════════ */
    .navbar {
        position: fixed; top: 0; left: 0; width: 100%; z-index: 1000;
        padding: 1.5rem 3rem;
        display: flex; align-items: center; justify-content: space-between;
        transition: background 0.5s ease, backdrop-filter 0.5s ease, padding 0.4s ease;
    }
    .navbar.is-scrolled {
        background: rgba(10,10,10,0.88);
        backdrop-filter: blur(25px);
        -webkit-backdrop-filter: blur(25px);
        padding-top: 1rem; padding-bottom: 1rem;
    }
    .navbar__logo {
        font-family: var(--font-heading);
        font-size: 1.4rem; font-weight: 800;
        letter-spacing: -0.03em; opacity: 0;
    }
    .navbar__logo span { color: var(--accent); }

    .navbar__links { display: flex; gap: 2.2rem; list-style: none; }
    .navbar__links li { opacity: 0; }
    .navbar__links a {
        font-family: var(--font-body);
        font-size: 0.78rem; font-weight: 500;
        letter-spacing: 0.1em; text-transform: uppercase;
        position: relative; padding-bottom: 3px;
        transition: color 0.3s ease;
    }
    .navbar__links a::after {
        content: ''; position: absolute; bottom: 0; left: 0;
        width: 100%; height: 1px; background: var(--accent);
        transform: scaleX(0); transform-origin: left;
        transition: transform 0.5s var(--ease-expo);
    }
    .navbar__links a:hover { color: var(--accent); }
    .navbar__links a:hover::after { transform: scaleX(1); }

    /* Hamburger */
    .hamburger {
        display: none; flex-direction: column; gap: 5px;
        width: 28px; padding: 4px 0; z-index: 1002;
        position: relative;
    }
    .hamburger span {
        display: block; width: 100%; height: 2px;
        background: var(--text);
        transition: transform 0.5s var(--ease-expo), opacity 0.3s ease;
        transform-origin: center;
    }
    .hamburger.is-active span:nth-child(1) { transform: translateY(7px) rotate(45deg); }
    .hamburger.is-active span:nth-child(2) { opacity: 0; }
    .hamburger.is-active span:nth-child(3) { transform: translateY(-7px) rotate(-45deg); }

    @media (max-width: 900px) {
        .navbar__links { display: none; }
        .hamburger { display: flex; }
        .navbar { padding: 1.2rem 1.5rem; }
    }

    /* ═══════════════════════════════════════════ */
    /*  MOBILE MENU OVERLAY                        */
    /* ═══════════════════════════════════════════ */
    .mobile-menu {
        position: fixed; inset: 0; z-index: 1001;
        background: var(--bg);
        display: flex; flex-direction: column;
        align-items: center; justify-content: center; gap: 0.8rem;
        clip-path: inset(0 0 100% 0);
        transition: clip-path 0.7s var(--ease-expo);
    }
    .mobile-menu.is-open { clip-path: inset(0 0 0 0); }

    .mobile-menu a {
        font-family: var(--font-heading);
        font-size: clamp(2rem, 6vw, 3.5rem);
        font-weight: 700; opacity: 0;
        transform: translateY(50px);
        transition: color 0.3s ease;
    }
    .mobile-menu a:hover { color: var(--accent); }

    .mobile-menu.is-open a {
        opacity: 1; transform: translateY(0);
        transition: opacity 0.5s ease, transform 0.6s var(--ease-expo), color 0.3s ease;
    }
    .mobile-menu.is-open a:nth-child(1) { transition-delay: 0.12s, 0.12s, 0s; }
    .mobile-menu.is-open a:nth-child(2) { transition-delay: 0.18s, 0.18s, 0s; }
    .mobile-menu.is-open a:nth-child(3) { transition-delay: 0.24s, 0.24s, 0s; }
    .mobile-menu.is-open a:nth-child(4) { transition-delay: 0.30s, 0.30s, 0s; }
    .mobile-menu.is-open a:nth-child(5) { transition-delay: 0.36s, 0.36s, 0s; }

    .mobile-menu__location {
        position: absolute; bottom: 2rem;
        font-size: 0.7rem; letter-spacing: 0.15em;
        text-transform: uppercase; color: var(--gray);
        opacity: 0;
    }
    .mobile-menu.is-open .mobile-menu__location {
        opacity: 1;
        transition: opacity 0.5s ease 0.5s;
    }

    /* ═══════════════════════════════════════════ */
    /*  FLOATING CONTACT BUTTON                    */
    /* ═══════════════════════════════════════════ */
    .floating-contact {
        position: fixed; bottom: 2rem; right: 2rem; z-index: 998;
        display: flex; flex-direction: column; align-items: center; gap: 0.5rem;
        opacity: 0;
    }
    .floating-contact__circle {
        width: 54px; height: 54px;
        border: 1.5px solid rgba(255,255,255,0.15);
        border-radius: 50%;
        display: flex; align-items: center; justify-content: center;
        transition: all 0.4s var(--ease-expo);
        position: relative;
    }
    .floating-contact__circle::before {
        content: ''; position: absolute; inset: -4px;
        border: 1px solid rgba(200,255,0,0);
        border-radius: 50%;
        transition: all 0.4s var(--ease-expo);
    }
    .floating-contact__circle svg {
        width: 20px; height: 20px;
        stroke: var(--text); fill: none; stroke-width: 1.5;
        transition: stroke 0.3s ease;
    }
    .floating-contact:hover .floating-contact__circle {
        transform: scale(1.08);
        border-color: var(--accent);
        background: rgba(200,255,0,0.05);
    }
    .floating-contact:hover .floating-contact__circle::before {
        border-color: rgba(200,255,0,0.2);
        inset: -8px;
    }
    .floating-contact:hover .floating-contact__circle svg { stroke: var(--accent); }
    .floating-contact__label {
        font-size: 0.6rem; letter-spacing: 0.15em;
        text-transform: uppercase; color: var(--gray);
    }

    @media (max-width: 768px) {
        .floating-contact { bottom: 1.2rem; right: 1.2rem; }
        .floating-contact__circle { width: 46px; height: 46px; }
    }

    /* ═══════════════════════════════════════════ */
    /*  HERO SECTION                               */
    /* ═══════════════════════════════════════════ */
    .hero {
        position: relative; min-height: 100vh; min-height: 100dvh;
        display: flex; flex-direction: column;
        justify-content: center;
        padding: 8rem 3rem 4rem;
        overflow: hidden;
    }
    .hero__bg {
        position: absolute; inset: 0; z-index: -2;
        background:
            radial-gradient(ellipse at 15% 50%, rgba(200,255,0,0.04) 0%, transparent 55%),
            radial-gradient(ellipse at 85% 20%, rgba(200,255,0,0.02) 0%, transparent 45%),
            var(--bg);
    }
    .hero__mesh {
        position: absolute; inset: 0; z-index: -1;
        opacity: 0.07;
        background:
            radial-gradient(circle at 25% 35%, var(--accent) 0%, transparent 45%),
            radial-gradient(circle at 75% 65%, #0047ff 0%, transparent 45%),
            radial-gradient(circle at 55% 85%, #ff2d55 0%, transparent 35%);
        filter: blur(100px);
        animation: meshFloat 15s ease-in-out infinite alternate;
    }
    @keyframes meshFloat {
        0%   { transform: scale(1) translate(0, 0) rotate(0deg); }
        33%  { transform: scale(1.05) translate(2%, -2%) rotate(1deg); }
        66%  { transform: scale(1.02) translate(-1%, 3%) rotate(-0.5deg); }
        100% { transform: scale(1.08) translate(-2%, 1%) rotate(0.5deg); }
    }

    .hero__location {
        position: absolute; top: 6.5rem; right: 3rem;
        font-size: 0.7rem; letter-spacing: 0.15em;
        text-transform: uppercase; color: var(--gray); opacity: 0;
    }

    .hero__title {
        font-family: var(--font-heading);
        font-size: clamp(2.8rem, 8vw, 7.5rem);
        font-weight: 800; line-height: 1.02;
        letter-spacing: -0.035em;
        max-width: 950px;
    }
    .hero__title .line { overflow: hidden; display: block; }
    .hero__title .line-inner { display: block; transform: translateY(110%); }

    .hero__subtitle {
        margin-top: 1.8rem;
        font-family: var(--font-body);
        font-size: clamp(0.85rem, 1.3vw, 1.05rem);
        font-weight: 300; letter-spacing: 0.2em;
        color: var(--gray); opacity: 0;
        text-transform: lowercase;
    }
    .hero__subtitle .pipe { color: rgba(255,255,255,0.15); margin: 0 0.7em; }

    .hero__cta { margin-top: 2.5rem; opacity: 0; }
    .hero__cta a {
        display: inline-flex; align-items: center; gap: 0.7rem;
        font-size: 0.8rem; font-weight: 500;
        letter-spacing: 0.1em; text-transform: uppercase;
        border-bottom: 1px solid rgba(255,255,255,0.2);
        padding-bottom: 5px;
        transition: border-color 0.3s ease, color 0.3s ease;
    }
    .hero__cta a:hover { color: var(--accent); border-color: var(--accent); }
    .hero__cta svg {
        width: 14px; height: 14px;
        transition: transform 0.3s var(--ease-expo);
    }
    .hero__cta a:hover svg { transform: translateX(4px); }

    .hero__scroll {
        position: absolute; bottom: 2.5rem; left: 50%;
        transform: translateX(-50%);
        display: flex; flex-direction: column; align-items: center; gap: 0.6rem;
        font-size: 0.6rem; letter-spacing: 0.2em;
        text-transform: uppercase; color: var(--gray); opacity: 0;
    }
    .hero__scroll-line {
        width: 1px; height: 45px; position: relative; overflow: hidden;
    }
    .hero__scroll-line::after {
        content: ''; position: absolute; top: -100%; left: 0;
        width: 1px; height: 100%; background: var(--accent);
        animation: scrollLine 2s ease-in-out infinite;
    }
    @keyframes scrollLine {
        0%   { top: -100%; opacity: 0; }
        20%  { opacity: 1; }
        80%  { opacity: 1; }
        100% { top: 100%; opacity: 0; }
    }

    @media (max-width: 768px) {
        .hero { padding: 7rem 1.5rem 3rem; }
        .hero__location { right: 1.5rem; top: 5.5rem; }
    }

    /* ═══════════════════════════════════════════ */
    /*  SERVICES SECTION                           */
    /* ═══════════════════════════════════════════ */
    .services {
        padding: 4rem 0 2rem;
    }
    .services__header {
        padding: 0 3rem 3rem;
        opacity: 0; transform: translateY(30px);
    }
    .services__label {
        font-size: 0.7rem; font-weight: 500;
        letter-spacing: 0.2em; text-transform: uppercase;
        color: var(--accent); margin-bottom: 0.8rem;
    }
    .services__heading {
        font-family: var(--font-heading);
        font-size: clamp(1.5rem, 3vw, 2.2rem);
        font-weight: 700; max-width: 550px;
        line-height: 1.2;
    }

    .service-block {
        display: grid; grid-template-columns: 1fr 1fr;
        gap: 3rem; align-items: center;
        padding: 5rem 3rem;
        border-top: 1px solid var(--border);
        position: relative;
    }
    .service-block:nth-child(odd) .service-block__image { order: 1; }
    .service-block:nth-child(odd) .service-block__content { order: 2; }
    .service-block:nth-child(even) .service-block__image { order: 2; }
    .service-block:nth-child(even) .service-block__content { order: 1; }

    .service-block__image {
        position: relative; overflow: hidden;
        border-radius: 4px; aspect-ratio: 4/3;
        clip-path: inset(100% 0 0 0);
    }
    .service-block__image-inner {
        width: 100%; height: 100%; object-fit: cover;
        transition: transform 0.7s var(--ease-expo);
    }
    .service-block:hover .service-block__image-inner { transform: scale(1.06); }

    /* Placeholder gradient images */
    .img--design {
        background: linear-gradient(145deg, #0d1117 0%, #161b22 30%, #1a2332 50%, #0f1923 100%);
        position: relative;
    }
    .img--design::after {
        content: ''; position: absolute; inset: 0;
        background:
            radial-gradient(circle at 30% 70%, rgba(200,255,0,0.08) 0%, transparent 50%),
            radial-gradient(circle at 70% 30%, rgba(0,100,255,0.06) 0%, transparent 50%);
    }
    .img--uiux {
        background: linear-gradient(145deg, #110d17 0%, #1a1225 30%, #221535 50%, #0f0a1a 100%);
        position: relative;
    }
    .img--uiux::after {
        content: ''; position: absolute; inset: 0;
        background:
            radial-gradient(circle at 60% 40%, rgba(150,50,255,0.08) 0%, transparent 50%),
            radial-gradient(circle at 20% 80%, rgba(200,255,0,0.05) 0%, transparent 50%);
    }
    .img--motion {
        background: linear-gradient(145deg, #170d0a 0%, #251510 30%, #2e1a0e 50%, #1a100a 100%);
        position: relative;
    }
    .img--motion::after {
        content: ''; position: absolute; inset: 0;
        background:
            radial-gradient(circle at 50% 50%, rgba(255,80,30,0.08) 0%, transparent 50%),
            radial-gradient(circle at 80% 20%, rgba(200,255,0,0.05) 0%, transparent 50%);
    }

    .service-block__number {
        font-family: var(--font-heading);
        font-size: clamp(5rem, 12vw, 11rem);
        font-weight: 800; line-height: 0.9;
        color: transparent;
        -webkit-text-stroke: 1px rgba(255,255,255,0.05);
        position: absolute; top: 2rem;
        opacity: 0; transform: translateX(-80px);
        user-select: none;
    }
    .service-block:nth-child(odd) .service-block__number { left: 2rem; }
    .service-block:nth-child(even) .service-block__number { right: 2rem; transform: translateX(80px); }

    .service-block__content { position: relative; z-index: 2; }

    .service-block__title {
        font-family: var(--font-heading);
        font-size: clamp(1.6rem, 3vw, 2.4rem);
        font-weight: 700; margin-bottom: 1.2rem;
        overflow: hidden;
    }
    .service-block__title-inner { display: block; transform: translateY(110%); }

    .service-block__text {
        font-size: 0.95rem; font-weight: 300;
        color: rgba(240,240,240,0.65); line-height: 1.75;
        max-width: 480px;
        opacity: 0; transform: translateY(25px);
    }
    .service-block__text strong { font-weight: 600; color: var(--text); }

    .service-block__link {
        display: inline-flex; align-items: center; gap: 0.6rem;
        margin-top: 1.8rem;
        font-size: 0.82rem; font-weight: 500;
        letter-spacing: 0.06em;
        opacity: 0; transform: translateY(15px);
        transition: color 0.3s ease;
    }
    .service-block__link:hover { color: var(--accent); }
    .service-block__link svg {
        width: 16px; height: 16px;
        transition: transform 0.4s var(--ease-expo);
    }
    .service-block__link:hover svg { transform: translateX(7px); }

    @media (max-width: 900px) {
        .service-block {
            grid-template-columns: 1fr; gap: 2rem;
            padding: 3rem 1.5rem;
        }
        .service-block:nth-child(even) .service-block__image { order: 1; }
        .service-block:nth-child(even) .service-block__content { order: 2; }
        .service-block__number { display: none; }
        .services__header { padding: 0 1.5rem 2rem; }
    }

    /* ═══════════════════════════════════════════ */
    /*  ABOUT / STUDIO SECTION                     */
    /* ═══════════════════════════════════════════ */
    .about {
        padding: 6rem 3rem;
        border-top: 1px solid var(--border);
        display: grid; grid-template-columns: 1fr 1fr;
        gap: 4rem; align-items: start;
    }
    .about__label {
        font-size: 0.7rem; font-weight: 500;
        letter-spacing: 0.2em; text-transform: uppercase;
        color: var(--accent); margin-bottom: 1.2rem;
    }
    .about__title {
        font-family: var(--font-heading);
        font-size: clamp(1.8rem, 3.5vw, 2.8rem);
        font-weight: 700; line-height: 1.15;
        margin-bottom: 2rem;
    }
    .about__text {
        font-size: 0.95rem; font-weight: 300;
        color: rgba(240,240,240,0.65); line-height: 1.8;
    }
    .about__text strong { font-weight: 600; color: var(--text); }
    .about__text p + p { margin-top: 1.2rem; }

    .about__stats {
        display: grid; grid-template-columns: 1fr 1fr;
        gap: 2rem; margin-top: 3rem;
    }
    .about__stat-number {
        font-family: var(--font-heading);
        font-size: clamp(2rem, 4vw, 3.2rem);
        font-weight: 800; color: var(--accent);
        line-height: 1;
    }
    .about__stat-label {
        font-size: 0.8rem; font-weight: 400;
        color: var(--gray); margin-top: 0.4rem;
        letter-spacing: 0.03em;
    }

    @media (max-width: 900px) {
        .about {
            grid-template-columns: 1fr;
            padding: 4rem 1.5rem; gap: 2rem;
        }
    }

    /* ═══════════════════════════════════════════ */
    /*  LOGOS MARQUEE                              */
    /* ═══════════════════════════════════════════ */
    .marquee-section {
        padding: 4.5rem 0;
        border-top: 1px solid var(--border);
        border-bottom: 1px solid var(--border);
        overflow: hidden;
    }
    .marquee-section__label {
        text-align: center;
        font-size: 0.65rem; font-weight: 500;
        letter-spacing: 0.2em; text-transform: uppercase;
        color: var(--gray-light); margin-bottom: 2.5rem;
    }
    .marquee-track {
        display: flex; gap: 4rem; align-items: center;
        width: max-content;
        animation: marqueeScroll 50s linear infinite;
    }
    @keyframes marqueeScroll {
        0%   { transform: translateX(0); }
        100% { transform: translateX(-50%); }
    }
    .marquee-track:hover { animation-play-state: paused; }

    .marquee-logo {
        font-family: var(--font-heading);
        font-size: 0.85rem; font-weight: 600;
        letter-spacing: 0.08em; text-transform: uppercase;
        white-space: nowrap;
        opacity: 0.25;
        transition: opacity 0.4s ease;
        user-select: none;
    }
    .marquee-logo:hover { opacity: 1; }

    /* ═══════════════════════════════════════════ */
    /*  FOOTER                                     */
    /* ═══════════════════════════════════════════ */
    .footer {
        padding: 8rem 3rem 3rem;
        text-align: center;
    }
    .footer__cta-label {
        font-size: 0.7rem; font-weight: 500;
        letter-spacing: 0.2em; text-transform: uppercase;
        color: var(--gray); margin-bottom: 1.5rem;
    }
    .footer__cta {
        font-family: var(--font-heading);
        font-size: clamp(2rem, 5vw, 4rem);
        font-weight: 800; letter-spacing: -0.02em;
        display: inline-block;
        transition: color 0.3s ease;
    }
    .footer__cta:hover { color: var(--accent); }
    .footer__cta-arrow {
        display: inline-block;
        transition: transform 0.4s var(--ease-expo);
        margin-left: 0.3em;
    }
    .footer__cta:hover .footer__cta-arrow { transform: translate(8px, -8px); }

    .footer__divider {
        width: 60px; height: 1px;
        background: var(--border);
        margin: 4rem auto;
    }
    .footer__logo {
        font-family: var(--font-heading);
        font-size: 1.2rem; font-weight: 800;
        letter-spacing: -0.02em; margin-bottom: 1rem;
    }
    .footer__logo span { color: var(--accent); }
    .footer__copy {
        font-size: 0.72rem; color: var(--gray-light);
        letter-spacing: 0.04em;
    }
    .footer__social {
        display: flex; justify-content: center; gap: 1.5rem;
        margin-top: 1.5rem;
    }
    .footer__social a {
        font-size: 0.75rem; font-weight: 500;
        letter-spacing: 0.08em; text-transform: uppercase;
        color: var(--gray);
        transition: color 0.3s ease;
    }
    .footer__social a:hover { color: var(--accent); }

    @media (max-width: 768px) {
        .footer { padding: 5rem 1.5rem 2rem; }
    }
    </style>
</head>

<body>
    <!-- ═══ GRAIN OVERLAY ═══ -->
    <div class="grain" aria-hidden="true"></div>

    <!-- ═══ CUSTOM CURSOR ═══ -->
    <div class="cursor" aria-hidden="true"></div>

    <!-- ═══ PRELOADER ═══ -->
    <div class="preloader" aria-hidden="true">
        <div class="preloader__logo">Founji<span>.</span></div>
        <div class="preloader__bar"><div class="preloader__bar-fill"></div></div>
    </div>

    <!-- ═══ MOBILE MENU ═══ -->
    <nav class="mobile-menu" aria-label="Menu mobile">
        <a href="#accueil">Accueil</a>
        <a href="#services">Services</a>
        <a href="https://portfolio.founji.com" target="_blank">Portfolio</a>
        <a href="#studio">Studio</a>
        <a href="#contact">Contact</a>
        <div class="mobile-menu__location">Lévis, QC — Canada</div>
    </nav>

    <!-- ═══ NAVBAR ═══ -->
    <header class="navbar" role="navigation">
        <a href="#accueil" class="navbar__logo">Founji<span>.</span></a>
        <ul class="navbar__links">
            <li><a href="#accueil">Accueil</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="https://portfolio.founji.com" target="_blank">Portfolio</a></li>
            <li><a href="#studio">Studio</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <button class="hamburger" aria-label="Ouvrir le menu">
            <span></span><span></span><span></span>
        </button>
    </header>

    <!-- ═══ FLOATING CONTACT ═══ -->
    <a href="mailto:contact@founji.com" class="floating-contact">
        <div class="floating-contact__circle">
            <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z" stroke-linecap="round" stroke-linejoin="round"/>
                <polyline points="22,6 12,13 2,6" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
        </div>
        <span class="floating-contact__label">Contact</span>
    </a>

    <!-- ═══════════════════════════════════════════ -->
    <!--  HERO                                       -->
    <!-- ═══════════════════════════════════════════ -->
    <section class="hero" id="accueil">
        <div class="hero__bg" aria-hidden="true"></div>
        <div class="hero__mesh" aria-hidden="true"></div>

        <div class="hero__location">Lévis, QC</div>

        <h1 class="hero__title">
            <span class="line"><span class="line-inner">Studio de création</span></span>
            <span class="line"><span class="line-inner">graphique &amp; digital</span></span>
        </h1>

        <p class="hero__subtitle">
            design <span class="pipe">|</span> ui/ux <span class="pipe">|</span> motion <span class="pipe">|</span> web <span class="pipe">|</span> ads
        </p>

        <div class="hero__cta">
            <a href="#studio">
                Découvrir le studio
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
            </a>
        </div>

        <div class="hero__scroll">
            <div class="hero__scroll-line"></div>
            Scroll
        </div>
    </section>

    <!-- ═══════════════════════════════════════════ -->
    <!--  SERVICES                                   -->
    <!-- ═══════════════════════════════════════════ -->
    <section class="services" id="services">

        <div class="services__header">
            <div class="services__label">Services</div>
            <h2 class="services__heading">Des solutions créatives sur mesure pour chaque besoin.</h2>
        </div>

        <!-- BLOC 01 — Design & Branding -->
        <article class="service-block">
            <div class="service-block__number">01</div>
            <div class="service-block__image">
                <div class="service-block__image-inner img--design"></div>
            </div>
            <div class="service-block__content">
                <h3 class="service-block__title">
                    <span class="service-block__title-inner">Design &amp; Branding</span>
                </h3>
                <p class="service-block__text">
                    <strong>Founji</strong> crée des identités visuelles uniques et mémorables. Du logotype à la charte graphique complète, en passant par le packaging et les supports print, chaque projet reflète l'essence de votre marque avec précision et créativité.
                </p>
                <a href="https://portfolio.founji.com" class="service-block__link" target="_blank">
                    En savoir +
                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
                </a>
            </div>
        </article>

        <!-- BLOC 02 — UI/UX & Web -->
        <article class="service-block">
            <div class="service-block__number">02</div>
            <div class="service-block__image">
                <div class="service-block__image-inner img--uiux"></div>
            </div>
            <div class="service-block__content">
                <h3 class="service-block__title">
                    <span class="service-block__title-inner">UI/UX &amp; Web Design</span>
                </h3>
                <p class="service-block__text">
                    Des interfaces intuitives aux sites web performants, <strong>Founji</strong> conçoit des expériences digitales où esthétique et fonctionnalité se rencontrent. Wireframes, prototypage, design système — chaque pixel est pensé pour l'utilisateur.
                </p>
                <a href="https://portfolio.founji.com" class="service-block__link" target="_blank">
                    En savoir +
                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
                </a>
            </div>
        </article>

        <!-- BLOC 03 — Motion & Publicité -->
        <article class="service-block">
            <div class="service-block__number">03</div>
            <div class="service-block__image">
                <div class="service-block__image-inner img--motion"></div>
            </div>
            <div class="service-block__content">
                <h3 class="service-block__title">
                    <span class="service-block__title-inner">Motion &amp; Publicité</span>
                </h3>
                <p class="service-block__text">
                    Du motion design aux campagnes publicitaires social media, <strong>Founji</strong> donne vie à vos idées. Des contenus visuels captivants qui marquent les esprits et génèrent des résultats concrets pour votre business.
                </p>
                <a href="https://portfolio.founji.com" class="service-block__link" target="_blank">
                    En savoir +
                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
                </a>
            </div>
        </article>
    </section>

    <!-- ═══════════════════════════════════════════ -->
    <!--  ABOUT / STUDIO                             -->
    <!-- ═══════════════════════════════════════════ -->
    <section class="about" id="studio">
        <div class="about__left">
            <div class="about__label">Le Studio</div>
            <h2 class="about__title">Founji, c'est quoi&nbsp;?</h2>
            <div class="about__text">
                <p>
                    Avec <strong>plus de 10 ans d'expérience</strong> en tant que Designer Graphique et Directeur Artistique, <strong>Youssef Founji</strong> a créé Founji Studio pour offrir un accompagnement créatif personnalisé aux entreprises ambitieuses.
                </p>
                <p>
                    De l'identité de marque au design d'interfaces en passant par le motion design et la publicité digitale — le studio couvre l'ensemble de vos besoins en communication visuelle avec un <strong>seul interlocuteur de confiance</strong>.
                </p>
                <p>
                    Basé à <strong>Lévis, Québec</strong>, Founji travaille avec des clients au Canada et à l'international pour donner vie à des projets authentiques et mémorables.
                </p>
            </div>
        </div>
        <div class="about__right">
            <div class="about__stats">
                <div>
                    <div class="about__stat-number">10+</div>
                    <div class="about__stat-label">Années d'expérience</div>
                </div>
                <div>
                    <div class="about__stat-number">50+</div>
                    <div class="about__stat-label">Projets réalisés</div>
                </div>
                <div>
                    <div class="about__stat-number">2</div>
                    <div class="about__stat-label">Continents</div>
                </div>
                <div>
                    <div class="about__stat-number">∞</div>
                    <div class="about__stat-label">Créativité</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ═══════════════════════════════════════════ -->
    <!--  MARQUEE LOGOS                              -->
    <!-- ═══════════════════════════════════════════ -->
    <section class="marquee-section" aria-label="Clients & Partenaires">
        <div class="marquee-section__label">Ils m'ont fait confiance</div>
        <div class="marquee-track">
            <span class="marquee-logo">Hyundai</span>
            <span class="marquee-logo">Chili's</span>
            <span class="marquee-logo">Client 3</span>
            <span class="marquee-logo">Client 4</span>
            <span class="marquee-logo">Client 5</span>
            <span class="marquee-logo">Client 6</span>
            <span class="marquee-logo">Client 7</span>
            <span class="marquee-logo">Client 8</span>
            <span class="marquee-logo">Client 9</span>
            <span class="marquee-logo">Client 10</span>
            <span class="marquee-logo">Client 11</span>
            <span class="marquee-logo">Client 12</span>
            <!-- Duplicate for infinite scroll -->
            <span class="marquee-logo">Hyundai</span>
            <span class="marquee-logo">Chili's</span>
            <span class="marquee-logo">Client 3</span>
            <span class="marquee-logo">Client 4</span>
            <span class="marquee-logo">Client 5</span>
            <span class="marquee-logo">Client 6</span>
            <span class="marquee-logo">Client 7</span>
            <span class="marquee-logo">Client 8</span>
            <span class="marquee-logo">Client 9</span>
            <span class="marquee-logo">Client 10</span>
            <span class="marquee-logo">Client 11</span>
            <span class="marquee-logo">Client 12</span>
        </div>
    </section>

    <!-- ═══════════════════════════════════════════ -->
    <!--  FOOTER                                     -->
    <!-- ═══════════════════════════════════════════ -->
    <footer class="footer" id="contact">
        <div class="footer__cta-label">Un projet en tête ?</div>
        <a href="mailto:contact@founji.com" class="footer__cta">
            Discutons<span class="footer__cta-arrow">↗</span>
        </a>
        <div class="footer__divider"></div>
        <div class="footer__logo">Founji<span>.</span></div>
        <p class="footer__copy">©2025 Founji — Youssef Founji — Tous droits réservés</p>
        <div class="footer__social">
            <a href="https://www.linkedin.com/in/yousseffounjii/" target="_blank">LinkedIn</a>
            <a href="https://portfolio.founji.com" target="_blank">Portfolio</a>
            <a href="https://www.pinterest.com/yousseffounjii/" target="_blank">Pinterest</a>
        </div>
    </footer>

    <!-- ═══════════════════════════════════════════ -->
    <!--  SCRIPTS                                    -->
    <!-- ═══════════════════════════════════════════ -->
    <script>
    (function() {
        'use strict';

        /* ═══════════════════════════════════════════ */
        /*  LENIS SMOOTH SCROLL                        */
        /* ═══════════════════════════════════════════ */
        const lenisInstance = new Lenis({
            duration: 1.2,
            easing: function(t) { return Math.min(1, 1.001 - Math.pow(2, -10 * t)); },
            smoothWheel: true,
            smoothTouch: false,
        });

        gsap.registerPlugin(ScrollTrigger);

        lenisInstance.on('scroll', ScrollTrigger.update);
        gsap.ticker.add(function(time) { lenisInstance.raf(time * 1000); });
        gsap.ticker.lagSmoothing(0);

        /* ═══════════════════════════════════════════ */
        /*  CUSTOM CURSOR                              */
        /* ═══════════════════════════════════════════ */
        var cursorEl = document.querySelector('.cursor');
        var cx = -50, cy = -50, tx = -50, ty = -50;

        if (window.matchMedia('(pointer: fine)').matches && cursorEl) {
            document.addEventListener('mousemove', function(e) {
                tx = e.clientX;
                ty = e.clientY;
            });

            (function loop() {
                cx += (tx - cx) * 0.12;
                cy += (ty - cy) * 0.12;
                cursorEl.style.left = cx + 'px';
                cursorEl.style.top = cy + 'px';
                requestAnimationFrame(loop);
            })();

            document.querySelectorAll('a, button, .service-block__image').forEach(function(el) {
                el.addEventListener('mouseenter', function() { cursorEl.classList.add('is-hover'); });
                el.addEventListener('mouseleave', function() { cursorEl.classList.remove('is-hover'); });
            });
        }

        /* ═══════════════════════════════════════════ */
        /*  PRELOADER                                  */
        /* ═══════════════════════════════════════════ */
        var preloader = document.querySelector('.preloader');
        var barFill = document.querySelector('.preloader__bar-fill');
        var preloaderLogo = document.querySelector('.preloader__logo');

        var loadTL = gsap.timeline({
            onComplete: function() {
                preloader.style.pointerEvents = 'none';
                runPageAnimations();
            }
        });

        loadTL
            .to(preloaderLogo, { opacity: 1, y: 0, duration: 0.5, ease: 'power2.out' }, 0)
            .to(barFill, { width: '100%', duration: 0.8, ease: 'power1.inOut' }, 0.2)
            .to(preloaderLogo, { opacity: 0, y: -10, duration: 0.3, ease: 'power2.in' }, 1.2)
            .to(barFill, { opacity: 0, duration: 0.2 }, 1.2)
            .to(preloader, {
                clipPath: 'inset(0 0 100% 0)',
                duration: 0.9,
                ease: 'power4.inOut'
            }, 1.3);

        /* ═══════════════════════════════════════════ */
        /*  MAIN PAGE ANIMATIONS                       */
        /* ═══════════════════════════════════════════ */
        function runPageAnimations() {

            // ─── Hero intro timeline ───
            var heroTL = gsap.timeline();

            heroTL
                .to('.navbar__logo', { opacity: 1, duration: 0.6, ease: 'power2.out' }, 0)
                .to('.navbar__links li', {
                    opacity: 1, duration: 0.4, ease: 'power2.out',
                    stagger: 0.06
                }, 0.1)
                .to('.hero__title .line-inner', {
                    y: '0%', duration: 1.1,
                    ease: 'power3.out',
                    stagger: 0.12
                }, 0.15)
                .to('.hero__subtitle', {
                    opacity: 1, duration: 0.7, ease: 'power2.out'
                }, 0.65)
                .fromTo('.hero__subtitle', { y: 15 }, { y: 0, duration: 0.7, ease: 'power2.out' }, 0.65)
                .to('.hero__location', { opacity: 1, duration: 0.5, ease: 'power2.out' }, 0.85)
                .to('.hero__cta', { opacity: 1, duration: 0.6, ease: 'power2.out' }, 0.95)
                .to('.hero__scroll', { opacity: 1, duration: 0.5, ease: 'power2.out' }, 1.15)
                .to('.floating-contact', { opacity: 1, duration: 0.5, ease: 'power2.out' }, 1.25);

            // ─── Navbar blur on scroll ───
            ScrollTrigger.create({
                start: 80,
                onEnter: function() { document.querySelector('.navbar').classList.add('is-scrolled'); },
                onLeaveBack: function() { document.querySelector('.navbar').classList.remove('is-scrolled'); },
            });

            // ─── Services header ───
            gsap.to('.services__header', {
                opacity: 1, y: 0, duration: 0.8, ease: 'power2.out',
                scrollTrigger: { trigger: '.services__header', start: 'top 85%' }
            });

            // ─── Service blocks ───
            document.querySelectorAll('.service-block').forEach(function(block, i) {
                var tl = gsap.timeline({
                    scrollTrigger: {
                        trigger: block,
                        start: 'top 80%',
                        end: 'bottom 20%',
                        toggleActions: 'play none none reverse',
                    }
                });

                var numEl = block.querySelector('.service-block__number');
                var imgEl = block.querySelector('.service-block__image');
                var titleEl = block.querySelector('.service-block__title-inner');
                var textEl = block.querySelector('.service-block__text');
                var linkEl = block.querySelector('.service-block__link');

                tl.to(imgEl, {
                    clipPath: 'inset(0 0 0 0)',
                    duration: 1.1, ease: 'power3.inOut'
                }, 0);

                if (numEl) {
                    tl.to(numEl, {
                        opacity: 1, x: 0,
                        duration: 0.9, ease: 'power2.out'
                    }, 0.2);
                }

                tl.to(titleEl, {
                    y: '0%', duration: 0.9, ease: 'power3.out'
                }, 0.3)
                .to(textEl, {
                    opacity: 1, y: 0, duration: 0.7, ease: 'power2.out'
                }, 0.5)
                .to(linkEl, {
                    opacity: 1, y: 0, duration: 0.5, ease: 'power2.out'
                }, 0.65);
            });

            // ─── Parallax on images ───
            document.querySelectorAll('.service-block__image-inner').forEach(function(img) {
                gsap.to(img, {
                    y: '-12%',
                    scrollTrigger: {
                        trigger: img.closest('.service-block'),
                        start: 'top bottom',
                        end: 'bottom top',
                        scrub: 1.5,
                    }
                });
            });

            // ─── About section ───
            gsap.from('.about__left', {
                opacity: 0, x: -40, duration: 0.9, ease: 'power2.out',
                scrollTrigger: { trigger: '.about', start: 'top 75%' }
            });
            gsap.from('.about__right', {
                opacity: 0, x: 40, duration: 0.9, ease: 'power2.out', delay: 0.2,
                scrollTrigger: { trigger: '.about', start: 'top 75%' }
            });

            // ─── Stats counter ───
            document.querySelectorAll('.about__stat-number').forEach(function(stat) {
                var text = stat.textContent;
                if (text === '∞') return;
                var num = parseInt(text);
                var suffix = text.replace(num, '');
                gsap.from(stat, {
                    textContent: 0,
                    duration: 2,
                    ease: 'power1.out',
                    snap: { textContent: 1 },
                    scrollTrigger: { trigger: stat, start: 'top 85%' },
                    onUpdate: function() {
                        stat.textContent = Math.round(parseFloat(stat.textContent)) + suffix;
                    }
                });
            });

            // ─── Footer ───
            gsap.from('.footer', {
                opacity: 0, y: 40, duration: 0.8, ease: 'power2.out',
                scrollTrigger: { trigger: '.footer', start: 'top 90%' }
            });
        }

        /* ═══════════════════════════════════════════ */
        /*  MOBILE MENU                                */
        /* ═══════════════════════════════════════════ */
        var hamburger = document.querySelector('.hamburger');
        var mobileMenu = document.querySelector('.mobile-menu');

        hamburger.addEventListener('click', function() {
            var isOpen = hamburger.classList.toggle('is-active');
            mobileMenu.classList.toggle('is-open');

            if (isOpen) {
                lenisInstance.stop();
            } else {
                lenisInstance.start();
            }
        });

        mobileMenu.querySelectorAll('a').forEach(function(link) {
            link.addEventListener('click', function() {
                hamburger.classList.remove('is-active');
                mobileMenu.classList.remove('is-open');
                lenisInstance.start();
            });
        });

        /* ═══════════════════════════════════════════ */
        /*  SMOOTH ANCHOR SCROLL                       */
        /* ═══════════════════════════════════════════ */
        document.querySelectorAll('a[href^="#"]').forEach(function(anchor) {
            anchor.addEventListener('click', function(e) {
                var href = anchor.getAttribute('href');
                if (href === '#') return;
                var target = document.querySelector(href);
                if (target) {
                    e.preventDefault();
                    lenisInstance.scrollTo(target, { offset: -80, duration: 1.5 });
                }
            });
        });

    })();
    </script>
</body>
</html>
