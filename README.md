# ÉLAN ATELIER — Production Salla Twilight Fashion Theme

**ÉLAN ATELIER** is a commercial-grade, high-fashion storefront theme engineered specifically for the Salla Twilight framework. Designed for luxury clothing brands, boutiques, and apparel retailers, it combines an editorial visual identity with native Web Component support and logical RTL/LTR localization.

---

## Features

- **Editorial Fashion Visual System:** High-aspect product galleries, clean display typography, generous whitespace, and responsive image scaling.
- **Native Dual LTR/RTL Support:** Complete localization for Arabic (RTL) and English (LTR) utilizing Twilight dictionary keys and CSS logical properties.
- **Performance Optimized:** Clean build architecture designed to keep production assets under **500 KB** (well within Salla's 1 MB limit).
- **Accessible & Responsive:** Mobile-first layout compliant with WCAG 2.2 AA standards and `prefers-reduced-motion` support.
- **Merchant Customization:** Built-in options via `twilight.json` for color themes, typography selection, and motion settings.

---

## Directory Structure

```text
elan-atelier/
├── .gitignore
├── LICENSE
├── README.md
├── package.json
├── tailwind.config.js
├── twilight.json
├── webpack.config.js
└── src/
    ├── assets/
    │   └── styles/
    │       └── app.css
    ├── locales/
    │   ├── ar.json
    │   └── en.json
    └── views/
        ├── components/
        │   ├── footer/
        │   │   └── footer.twig
        │   ├── header/
        │   │   └── header.twig
        │   ├── home/
        │   │   ├── editorial-hero.twig
        │   │   └── lookbook.twig
        │   └── products/
        │       ├── product-card.twig
        │       └── size-selector.twig
        └── layouts/
            └── master.twig
