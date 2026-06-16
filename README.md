# Mis Notas — Instrucciones de instalación

## ¿Qué es esto?
Una app de notas completa (PWA) que podés instalar en tu iPad como si fuera una app nativa, sin App Store ni pago.

---

## Paso 1 — Subir a GitHub Pages

### 1.1 Crear repositorio
1. Andá a **github.com** e iniciá sesión (o creá una cuenta gratis)
2. Hacé clic en **"New repository"** (botón verde, arriba a la derecha)
3. Nombre del repositorio: `mis-notas` (todo minúsculas, sin espacios)
4. Dejalo en **Public**
5. Hacé clic en **"Create repository"**

### 1.2 Subir los archivos
Una vez creado el repositorio, vas a ver una página vacía. Hacé clic en **"uploading an existing file"**.

Subí **todos** estos archivos (arrastrá o seleccioná):
```
index.html
manifest.json
sw.js
icons/
  icon-192.png
  icon-512.png
  apple-touch-icon.png
```

> ⚠️ Para la carpeta `icons/`, primero subí los 3 archivos .png y después ponelos adentro de una carpeta `icons` desde la interfaz, o usá GitHub Desktop.

Escribí un mensaje de commit (ej: "primera versión") y hacé clic en **"Commit changes"**.

### 1.3 Activar GitHub Pages
1. Andá a **Settings** (engranaje, arriba del repo)
2. En el menú izquierdo, hacé clic en **"Pages"**
3. En "Source", seleccioná **"Deploy from a branch"**
4. En "Branch", seleccioná **main** y la carpeta **/ (root)**
5. Hacé clic en **Save**

Esperá 1-2 minutos. Tu app va a estar disponible en:
```
https://TU_USUARIO.github.io/mis-notas/
```

---

## Paso 2 — Instalar en el iPad

1. Abrí **Safari** en el iPad (tiene que ser Safari, no Chrome)
2. Andá a tu URL: `https://TU_USUARIO.github.io/mis-notas/`
3. Tocá el botón de **Compartir** (cuadrado con flecha hacia arriba)
4. Desplazate hacia abajo y tocá **"Agregar a la pantalla de inicio"**
5. Poné el nombre que quieras y tocá **"Agregar"**

¡Listo! Ya aparece el ícono en tu pantalla de inicio y funciona como una app nativa.

---

## Características incluidas

- ✅ Carpetas y subcarpetas ilimitadas
- ✅ Cuadernos con páginas cuadriculadas, rayadas o en blanco
- ✅ Escritura a mano con Apple Pencil / stylus
- ✅ Herramientas: lapicera, marcador, borrador, texto
- ✅ Deshacer trazos
- ✅ Páginas ilimitadas por cuaderno
- ✅ Exportar como PNG
- ✅ Exportar como PDF
- ✅ Todo se guarda automáticamente en el dispositivo
- ✅ Funciona sin internet (offline) una vez instalada
- ✅ Compatible con iPad y PC (desde el navegador)

---

## Acceso desde la PC

Desde cualquier navegador en tu PC, entrá a la misma URL:
```
https://TU_USUARIO.github.io/mis-notas/
```
Las notas se guardan localmente en cada dispositivo por separado.

---

## Soporte

Si algo no funciona, fijate que:
- Estés usando **Safari** para instalar (en iPad)
- El repositorio sea **público** en GitHub
- Hayas activado **GitHub Pages** en Settings
