# Web Facturación

Página web de una factura profesional maquetada con **HTML5** y **CSS3** puro, sin frameworks ni JavaScript.

🔗 **Demo en vivo:** https://pier0del.github.io/Web-Facturacion/

---

## Vista general

Factura de demostración para la empresa ficticia *Limitless Studio S.L.* que incluye datos del emisor, datos del cliente, tabla de conceptos con totales e información de pago.

---

## Características

- Maquetación con **CSS Grid** y **Flexbox**
- **Variables CSS** (`--bg`, `--accent`, `--border`...) para un tema consistente
- **HTML semántico**: `<address>`, `<time>`, `<dl>`, `<thead>`, `<tfoot>`, `<caption>`
- **Accesibilidad**: atributos `aria-label`, `role`, clase `.sr-only` para lectores de pantalla
- **Diseño responsive**: adaptado a móvil con `@media (max-width: 720px)`
- Scroll horizontal en tabla cuando la pantalla es pequeña
- Sin dependencias externas

---

## Estructura del proyecto

```
Web-Facturacion/
├── index.html       → Estructura y contenido de la factura
├── css/
│   └── style.css    → Estilos, variables y responsive
├── LICENSE
└── README.md
```

---

## Cómo verlo en local

1. Clona el repositorio:

```bash
git clone https://github.com/pier0del/Web-Facturacion.git
```

2. Abre `index.html` directamente en tu navegador. No necesita servidor ni instalación.

---

## Tecnologías usadas

- HTML5
- CSS3 (Grid, Flexbox, Custom Properties, Media Queries)

---

## Autor

Desarrollado por **Piero** — Proyecto educativo de maquetación web enfocado en HTML semántico, accesibilidad y diseño responsive sin frameworks.
