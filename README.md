# Oscar Camareña Yañez - Portfolio Profesional

Sitio web de portafolio profesional para Economista y Analista de Datos.

## Tecnologías

- **Framework**: Next.js 14 (App Router) con TypeScript
- **Estilos**: Tailwind CSS
- **Animaciones**: Framer Motion
- **Iconos**: Lucide React
- **Visualización de Datos**: D3.js, Recharts
- **Utilidades**: clsx, tailwind-merge

## 🚀 Despliegue en Vercel (Recomendado - Gratuito)

Para hacer el sitio público automáticamente:

1. **Instalar Node.js** desde [nodejs.org](https://nodejs.org) (versión LTS)
2. **Crear cuenta en Vercel** en [vercel.com](https://vercel.com)
3. **Subir el código a GitHub**:
   - Crear un repositorio nuevo en GitHub
   - Subir todos los archivos del proyecto
4. **Conectar con Vercel**:
   - En Vercel, hacer clic en "Add New Project"
   - Importar el repositorio de GitHub
   - Vercel detectará automáticamente que es un proyecto Next.js
   - Hacer clic en "Deploy"

Vercel creará automáticamente un dominio público como: `https://tu-portfolio.vercel.app`

## 💻 Ejecutar Localmente

1. Instalar Node.js desde [nodejs.org](https://nodejs.org)
2. Abrir terminal en la carpeta del proyecto
3. Instalar dependencias:
```bash
npm install
```
4. Ejecutar servidor de desarrollo:
```bash
npm run dev
```
5. Abrir [http://localhost:3000](http://localhost:3000) en el navegador

## Estructura del Proyecto

```
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── Header.tsx
│   ├── Hero.tsx
│   ├── Timeline.tsx
│   ├── Services.tsx
│   ├── Resources.tsx
│   ├── Portfolio.tsx
│   ├── InteractiveDemos.tsx
│   ├── Testimonials.tsx
│   └── Footer.tsx
├── lib/
│   └── utils.ts
├── public/
│   ├── profile-photo.jpg
│   └── CV_OSCAR_CAMARENA.pdf
├── vercel.json
└── package.json
```

## Secciones

1. **Header**: Navegación sticky con foto de perfil y enlaces anclados
2. **Hero**: Introducción interactiva con canvas D3.js
3. **Timeline**: Trayectoria profesional cronológica
4. **Services**: Matriz de servicios 2x2
5. **Resources**: Ecosistema de recursos abiertos
6. **Portfolio**: Proyectos con sistema de filtrado
7. **InteractiveDemos**: Calculadoras interactivas (OLS, Lorenz)
8. **Testimonials**: Carrusel de testimonios
9. **Footer**: Contacto con copiado de email

## Build para Producción

```bash
npm run build
npm start
```
