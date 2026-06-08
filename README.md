# pabloguolo.com.ar

Sitio web profesional de Dr. Pablo Guolo — Abogado.

## Estructura

```
.
├── index.html         ← La página (no toques esto)
├── contenido.json     ← Edita AQUÍ los textos, números, contactos
├── .gitignore         ← Archivos ignorados por Git
└── README.md          ← Este archivo
```

## ¿Cómo editar?

### Cambiar textos, números, contacto:

1. Abrí `contenido.json` en GitHub
2. Clickeá el lápiz (edit)
3. Cambias lo que quieras
4. Commit (guardás)
5. **En 30 segundos, la página en vivo está actualizada**

Ejemplos:
- Cambiar email: `"email": "nuevo@email.com"`
- Cambiar teléfono: `"whatsapp": "549XXXXXXXXXX"`
- Cambiar descripción de área: Editas el `"descripcion"` dentro de cada área

### Cambiar colores, fonts, layout:

Eso está en `index.html`. Es más complicado — necesitás saber HTML/CSS o pedirme ayuda.

## Deploy

Netlify se encarga automáticamente:
1. Vos hacés commit en GitHub
2. Netlify ve el cambio
3. En ~30 segundos redeploy automático
4. Listo

## DNS

Tu dominio `pabloguolo.com.ar` debe apuntar a Netlify:

Cambiá los nameservers en tu registrador a:
- `dns1.netlify.com`
- `dns2.netlify.com`

Esperá 24-48hs propagación.

## Contacto / Soporte

Si necesitás cambiar algo más complejo (estructura, agregar secciones), escribime.

---

© 2025 Pablo Guolo — CABA, Argentina
