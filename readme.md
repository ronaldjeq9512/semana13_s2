# Node.js Project Setup

## Instalación de NVM

NVM (Node Version Manager) es una herramienta que permite instalar y gestionar múltiples versiones de Node.js en una misma máquina. Es especialmente útil para trabajar en proyectos que requieren diferentes versiones de Node.js.

### Instalación de NVM

Para instalar NVM, puedes seguir estos pasos:

1. Entrar al siguiente link https://github.com/coreybutler/nvm-windows/releases/download/1.1.12/nvm-setup.exe
2. Dar siguiente a todo

### Importancia de NVM

NVM es crucial para gestionar proyectos con diferentes requisitos de versiones de Node.js. Facilita el cambio entre versiones de Node.js sin afectar otros proyectos en tu máquina.

### Por qué utilizar NPM y desinstalar Node.js LTS 
-Generará conflictos al momento de instalar y usar node

### Inicialización de un proyecto con Node.js

1. **Inicializar un proyecto**:
    ```sh
    mkdir mi-proyecto
    cd mi-proyecto
    npm init
    ```
2. **Seguir las instrucciones**
3. **Instalar dependencias de desarrollo**:
    ```sh
    npm install --save-dev eslint jest
    ```
4. **Instalar dependencias de producción**:
    ```sh
    npm install express mongoose
    ```
5. **Instalar dependencias globales**:
    ```sh
    npm install -g nodemon
    ```
