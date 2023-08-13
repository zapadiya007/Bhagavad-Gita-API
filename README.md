# Bhagavad Gita DevVeda
All Chapters Name with Summary 

![The Bhagavad Gita](https://repository-images.githubusercontent.com/314205765/0bb18d80-2b22-11eb-8f6f-ccf20c0c2679)


### React App Deploy on GitHub :

- Create React Basic App
- Create Repository on GitHub
- GitHub Pages Dependency install on React App  |  `npm install --save gh-pages`
- Add homepage url on package.josn  |  `"homepage": "http://zpadiya007.github.io/Bhagavad-Gita-API",`
- Add 2 Command in package.josn/"scripts"  |  `"predeploy":"npm run build","deploy":"gh-pages -d build",`
- Git initials in React App Folder then add in stage and commit

```
git init
git add .
git commit -m "Commit React app before deploy"
git remote add origin https://github.com/zapadiya007/Bhagavad-Gita-API.git
```

- Deploy Command Run  |  `npm run deploy`
- Automatically Upload Code on GitHub (Only Deploy Code)
- Depoly Your Website to GitHub Pages
