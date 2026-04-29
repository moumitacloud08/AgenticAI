"# AgenticAI" 

echo "# AgenticAI" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/moumitacloud08/AgenticAI.git
git push -u origin main

echo agents/ >> .gitignore
git add .gitignore
git commit -m "Ignore agents folder"
git push
