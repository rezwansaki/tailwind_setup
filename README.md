### Tailwind CSS 

This is a full basic and first step project to help another project. Actually this is a format or setup or a template. 

### How to use:
1. Download this project from GitHub
2. npm install
3. npm run build
4. Copy index.html from src folder and paste it in the build folder 
5. Modify index.html from build folder and create more html files if you want. The build folder is your final product. You can use this folder as your html template.
6. npm run build 
7. You will get the final product from 'build' folder. Copy the 'build' folder and rename if you want. 
8. Run 'index.html' file from build folder. 

### Tips:
1. After finishing 1 to 5 steps, open tailwind.config.js file and see the 'purge: { enabled: true' ..., just remove 'true' and write 'false'. Save this file. 
2. now 'npm run build' and you will get all tailwind css code in your build/css/style.css file. 
3. now you can work with your html files and run that html file very quickly. because, you don't need run 'build' command again and again. 
4. when your work is finished and you want the final product, just open tailwind.config.js file and see the 'purge: { enabled: false' ..., now remove 'false' and write 'true'. Save this file.  
5. 'npm run build' and you will get your final product. 