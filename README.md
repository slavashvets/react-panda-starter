# React + PandaCSS Starter (ffizer template)

A lean template for building React applications with **Bun**, **Vite**, **React 19.1**, and **Panda CSS**.  
It is packed as an **ffizer** blueprint, so you can scaffold a project without cloning or copying files by hand.

## Quick start

```bash
mkdir my-new-project
cd my-new-project
git init

# apply the template to the current folder
ffizer apply --source https://github.com/slavashvets/react-panda-starter --rev main --destination .

# run the development stack
task dev
````

`task dev` performs a self-check: it installs missing dependencies (Bun packages, git hooks, etc.) and then launches the Vite dev server.

## What’s inside

* **Bun** – configuration for Bun as the runtime and package manager
* **Vite 6** with `@vitejs/plugin-react-swc`
* **React 19.1**
* **Panda CSS** for type-safe styling
* **Taskfile** workflow wrapper
* **Lefthook + Biome** pre-commit linting
