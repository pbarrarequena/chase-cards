# 💳 Calculadora de Tarjetas Chase

Una aplicación web progresiva (PWA) para optimizar el uso de tus tarjetas Chase y maximizar tu período de float.

## 🚀 Características

- ✅ Calculadora inteligente de fechas
- 📱 Funciona como app en iPhone/Android
- 🔌 Funciona completamente sin conexión
- 🎨 Interfaz moderna y responsive
- ⚡ Recomendaciones instantáneas
- 📊 Cálculo automático de float

## 📱 Instalación en iPhone

1. Abre el link en Safari: `https://TU-USUARIO.github.io/chase-cards-calculator`
2. Toca el botón **Compartir** (cuadrito con flecha)
3. Selecciona **"Agregar a Pantalla de Inicio"**
4. ¡Listo! Ya tienes la app en tu iPhone

## 🛠️ Cómo Subir a GitHub Pages

### Paso 1: Crea un repositorio en GitHub
1. Ve a https://github.com/new
2. Nombre del repositorio: `chase-cards-calculator`
3. Marca como **Public**
4. No inicialices con README (ya tenemos uno)
5. Click en **Create repository**

### Paso 2: Sube los archivos
Tienes dos opciones:

#### Opción A: Usando la interfaz web de GitHub (MÁS FÁCIL)
1. En tu nuevo repositorio, click en **"uploading an existing file"**
2. Arrastra estos archivos:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `README.md`
3. Click en **Commit changes**

#### Opción B: Usando Git desde terminal
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/chase-cards-calculator.git
git push -u origin main
```

### Paso 3: Activa GitHub Pages
1. En tu repositorio, ve a **Settings** → **Pages**
2. En **Source**, selecciona **"main"** branch
3. Click en **Save**
4. Espera 1-2 minutos
5. Tu app estará disponible en: `https://TU-USUARIO.github.io/chase-cards-calculator`

## 📋 Tarjetas Incluidas

- **Chase Freedom Flex** (5738) - Cierra día 7
- **Amazon Prime Visa** (6556) - Cierra día 2
- **Chase Sapphire Preferred** (8625) - Cierra día 21
- **Chase Freedom Unlimited** (3214) - Cierra día 25

## 🎯 Cómo Usar

1. Selecciona la fecha de tu compra
2. (Opcional) Ingresa el monto
3. Click en "Calcular Mejor Tarjeta"
4. Recibe recomendación personalizada con días de float

## 🔧 Tecnologías

- HTML5
- CSS3 (Responsive Design)
- JavaScript (Vanilla)
- PWA (Service Worker + Manifest)

## 📄 Licencia

Uso personal - Pablo Barra © 2026

---

**Nota**: Esta app funciona completamente offline una vez instalada. No requiere conexión a internet después de la primera carga.
