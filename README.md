
# Portfolio Website

Un projet de site portfolio construit avec Vite, React (TypeScript) et Tailwind CSS, inspiré du design Figma : https://www.figma.com/design/uzi8L8164UFUcwkwWDDym8/Portfolio-website.

## 🚀 À propos

- Single Page Application (SPA) pour un portfolio personnel
- Interface responsive pour mobile et desktop
- Contient des sections : Accueil, Projets, Contact
- Composants UI modulaires réutilisables (button, card, modal, etc.)
- Système de gestion de la langue via `LanguageContext`

## 🧱 Stack technique

- `React` + `TypeScript`
- `Vite` comme bundler
- `Tailwind CSS` + `@tailwindcss/forms` (ou équivalent) pour le style
- Composants UI personnalisés dans `src/app/components/ui`
- Routing via `react-router-dom` ou système de fichiers (selon config)

## 📁 Structure du projet

- `src/main.tsx` : point d’entrée
- `src/app/App.tsx` : composant racine
- `src/app/routes.ts` : définition des routes/pages
- `src/app/components` : composants de pages et de projet
- `src/app/components/ui` : primitives UI custom
- `src/app/context/LanguageContext.tsx` : contexte de langue
- `src/styles` : CSS global et thème

## ▶️ Exécution locale

1. Installer les dépendances
   - `npm install`

2. Démarrer le serveur de dev
   - `npm run dev`

3. Ouvrir dans le navigateur (URL indiquée dans le terminal, typiquement `http://localhost:5173`)

## 🧩 Scripts utiles

- `npm run dev` : serveur de développement
- `npm run build` : build de production
- `npm run preview` : prévisualiser le build de production localement
- `npm run lint` : analyse/lint (si configuré)

## 📦 Déploiement

- Déployer le dossier `dist` sur Netlify / Vercel / GitHub Pages / Surge
- Pour Vercel : créer un projet, référencer le repo, build command : `npm run build`, output dir : `dist`

## 🛠️ Personnalisation rapide

- Modifier les couleurs et typographies dans `src/styles/theme.css`
- Ajuster la grille et les breakpoints dans `tailwind.config.ts` (si utilisé)
- Ajouter de nouveaux projets dans `src/app/components/Projects.tsx` ou source de données dédié

## 📌 Contribution

1. Forker le repo
2. Créer une branche de feature (`git checkout -b feature/nom`)
3. Commit et push
4. Ouvrir une PR

## 📄 License

MIT (à adapter au besoin)
  
