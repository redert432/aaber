git init
git remote add origin https://github.com/USERNAME/aaber.git
git add .
git commit -m "إصدار أولي"
git push -u origin main

"homepage": "https://USERNAME.github.io/aaber",
"scripts": {
"predeploy": "npm run build",
"deploy": "gh-pages -d dist" // أو build حسب الأداة
}

https://USERNAME.github.io/aaber
