
# Setup
## 1 Local server: Node
1. install node.js (check version `node -v`)
2. check npm version `npm -v`

## 2 Track changes: git
1. install git (check version `git --version`)
2. `$git init $git add . $git commit -m "initial commit" $git remote add origin <your-repo-url> $git push -u origin main`
3. add `.gitignore` file to not track changes is certain files/folders


## 3 Install packages: [npm](https://www.w3schools.com/nodejs/nodejs_package_json.asp)

1. `npm init`
[npm init](https://weaintplastic.github.io/web-development-field-guide/Development/Frontend_Development/Setting_up_your_project/Setup_Dependency_Managers/Node_Package_Manager/Initialize_NPM_on_a_new_project.html)

2. `npm install` will use package.json and generate `package-lock.json` and `node_modules/`

3. before running any command we need to install the plugins 
`npm install -D vite`

4. npm install adds a line in the package.json's dependencies. Remove the range in the package version for precise control: 
`^1.2`->`1.2.3` 


## 4 Project builder: [vite](https://vite.dev/guide/)

1. run packages commands `npx vite -v`

2. `npm create vite@latest <project> -- --template react-ts`

3. `vite.config.js` react

## 5 Langage support: typescript

1. `npm install --save-dev @types/react @types/react-dom`

2. `tsconfig.json` file for the compiler

## 6 Code transpiler: [Babel](https://babeljs.io/docs/usage)
1. `npm install --save-dev @babel/core @babel/cli @babel/preset-env` for ES6 support
2. `npm install --save-dev @babel/preset-react` for JSX support
3. `babel.config.json`

## 7 Code formatting: Prettier

## 8 Code quality tools:ESLint

## 9 Security: env
1. environment variables in `.env` file
2. 

[12factor](https://12factor.net/)

## Testing framework: Vitest

## API client: [SWR](https://swr.vercel.app/)

## Full stack framework: nextjs
nextjs for full stack development

## CI
