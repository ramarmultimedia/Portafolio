# 🌟 Mi Portafolio Personal

[![Astro](https://img.shields.io/badge/Astro-FF5A1F?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

> Apendiendo a crear portafolio web moderno y responsivo construido con Astro, diseñado para mostrar mis habilidades, proyectos y experiencia profesional de manera elegante y funcional.

## ✨ Características

- **⚡ Rendimiento optimizado**: Construido con Astro para una carga ultrarrápida
- **📱 Diseño responsivo**: Se adapta perfectamente a todos los dispositivos
- **🎨 Interfaz moderna**: Diseño limpio y profesional con animaciones suaves
- **📄 Generación estática**: Sitio completamente estático para máximo rendimiento

## 🛠️ Tecnologías Utilizadas

- **[Astro](https://astro.build/)** - Framework principal para generación estática
- **[TypeScript](https://www.typescriptlang.org/)** - Tipado estático para mayor robustez
- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS para estilos utilitarios
- **[Vanilla JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)** - Interactividad del lado del cliente

## 📁 Estructura del Proyecto

```
/
├── public/                 # Archivos estáticos
│   ├── favicon.svg        # Favicon del sitio
│   └── images/            # Imágenes y recursos
├── src/
│   ├── assets/            # Assets procesados por Astro
│   ├── components/        # Componentes reutilizables
│   │   ├── Header.astro   # Encabezado de navegación
│   │   ├── Footer.astro   # Pie de página
│   │   └── Card.astro     # Tarjetas de proyectos
│   ├── layouts/           # Plantillas de diseño
│   │   └── Layout.astro   # Layout principal
│   ├── pages/             # Páginas del sitio
│   │   ├── index.astro    # Página de inicio
│   │   ├── about.astro    # Acerca de mí
│   │   └── projects.astro # Portafolio de proyectos
│   └── styles/            # Estilos globales
└── package.json
```

## 🚀 Instalación y Uso

### Prerrequisitos

- [Node.js](https://nodejs.org/) (versión 18 o superior)
- [pnpm](https://pnpm.io/) (recomendado) o npm

### Configuración Local

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/ramarmultimedia/Portafolio.git
   cd Portafolio
   ```

2. **Instalar dependencias**
   ```bash
   pnpm install
   # o
   npm install
   ```

3. **Ejecutar en modo desarrollo**
   ```bash
   pnpm dev
   # o
   npm run dev
   ```
   
   El sitio estará disponible en `http://localhost:4321`

### Comandos Disponibles

| Comando | Descripción |
|---------|-------------|
| `pnpm dev` | Inicia el servidor de desarrollo |
| `pnpm build` | Construye el sitio para producción |
| `pnpm preview` | Vista previa del build de producción |
| `pnpm astro check` | Verifica errores de TypeScript |
| `pnpm astro add <integration>` | Añade integraciones de Astro |

## 🎨 Personalización

### Modificar Contenido

1. **Información personal**: Edita los datos en `src/pages/index.astro`
2. **Proyectos**: Actualiza la sección de proyectos en `src/pages/projects.astro`
3. **Estilos**: Personaliza los colores y diseño en los archivos de componentes
4. **Imágenes**: Reemplaza las imágenes en la carpeta `public/images/`

### Añadir Nuevas Páginas

Crea nuevos archivos `.astro` en `src/pages/` y automáticamente se generarán las rutas correspondientes.

## 📱 Secciones del Portafolio

- **🏠 Inicio**: Presentación personal y enlaces de contacto
- **👨‍💻 Acerca de**: Información detallada sobre habilidades y experiencia
- **💼 Proyectos**: Showcase de trabajos y proyectos destacados
- **📞 Contacto**: Formulario de contacto y redes sociales

## 🌐 Deploy

### Netlify (Recomendado)
```bash
pnpm build
# Sube la carpeta dist/ a Netlify
```

### Vercel
```bash
# Conecta tu repositorio de GitHub con Vercel
# El deploy será automático con cada push
```

### GitHub Pages
```bash
# Configura GitHub Actions para deploy automático
# Ver: https://docs.astro.build/en/guides/deploy/github/
```

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 📞 Contacto

**Ramar Multimedia**
- 🌐 Sitio web: [Tu sitio web]
- 💼 LinkedIn: [Tu perfil de LinkedIn](https://linkedin.com/in/jesús-andrés-ramos-martínez-15a7a4301)
- 🐙 GitHub: [@ramarmultimedia](https://github.com/ramarmultimedia)

## 🙏 Agradecimientos

- [Astro Team](https://astro.build/) por este increíble framework
- [Tailwind CSS](https://tailwindcss.com/) por el sistema de diseño
- [Iconos de Heroicons](https://heroicons.com/) por los iconos utilizados
- Comunidad de desarrolladores por la inspiración y retroalimentación

---

<div align="center">
  <p>⭐ Si te gusta este proyecto, ¡no olvides darle una estrella! ⭐</p>
</div>
