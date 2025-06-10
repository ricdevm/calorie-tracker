# Calorie Tracker – React + TypeScript + Tailwind CSS

Esta aplicación web permite registrar y visualizar las calorías consumidas mediante alimentos y las calorías quemadas a través de actividades físicas. Está desarrollada con **React** y **TypeScript**, y utiliza **Context API** junto con el hook **useReducer** para gestionar el estado global de manera eficiente y escalable.

## Características principales

- **React + TypeScript**: Tipado estático y componentes modernos.
- **Context API + useReducer**: Manejo global del estado de actividades y calorías.
- **Tailwind CSS**: Estilos modernos, responsivos y personalizables.
- **Persistencia en localStorage**: Guarda los datos incluso al cerrar el navegador.
- **Hooks personalizados**: Lógica centralizada y reutilizable con React hooks.
- **Heroicons**: Íconos simples y modernos para mejorar la interfaz.

## Librerías utilizadas

- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Heroicons](https://heroicons.com/)

## Scripts principales

```bash
npm install      # Instala todas las dependencias
npm run dev      # Inicia el servidor de desarrollo
npm run build    # Genera la build de producción
```

## Estructura del proyecto

- `/src/components` — Componentes de la interfaz de usuario.
- `/src/context` — Definición del contexto y proveedor global.
- `/src/reducers` — Lógica de reducción para el manejo del estado.
- `/src/hooks` — Hooks personalizados para manejo de actividades.
- `/src/data` — Datos estáticos como categorías.
- `/src/App.tsx` — Componente principal de la aplicación.
- `/src/main.tsx` — Punto de entrada de la aplicación.

## Notas
- El uso de Context API junto con useReducer permite una estructura escalable y una lógica de estado clara.
- La información de las actividades (comidas y ejercicios) se guarda automáticamente en el localStorage.
- El diseño es completamente responsivo y puede personalizarse fácilmente con Tailwind CSS.
- Puedes extender el proyecto añadiendo filtros, categorías personalizadas o integración con una API externa.

¡Clona este repositorio y comienza a llevar el control de tus calorías de manera eficiente!