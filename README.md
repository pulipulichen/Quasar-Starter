# Quasar-Starter
Build a PWA and Electron application based on Quasar framework.

----

# Installation

1. Install node, git and docker-compose in your computer.
2. Fork `https://github.com/pulipulichen/Quasar-Starter` to your repository.
3. Clone your repository. For example: `git clone https://github.com/pulipulichen/Quasar-Starter.git`
4. `cd Quasar-Starter`
5. `npm run docker-build`

----

# Development

## For PWA

1. `npm run dev-pwa`
2. Open browser: http://localhost:8080/

## For AppImage

1. `npm run dev-electron`
2. Application will display on your screen.

You can edit source codes in `app/src/` to modify your application. 

----

# Build

## For PWA

1. `npm run build-pwa`
2. You can find files in `/app/dist/pwa/` .

## For AppImage

1. `npm run build-appimage`
2. You can find the AppImage file in `/app/dist/electron/Packaged/` .