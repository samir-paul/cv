## SamirPaul1/blog

Live Demo: [![Deploy Hugo site to Pages](https://github.com/SamirPaul1/blog/actions/workflows/hugo.yml/badge.svg)](https://github.com/SamirPaul1/blog/actions/workflows/hugo.yml) \
👉 **https://samirpaul1.github.io/blog** 


Created using [Hugo](https://gohugo.io/getting-started/installing/) and [PaperMod](https://github.com/SamirPaulb/hugo-PaperMod).

Steps:
1. Install Hugo ```choco install hugo-extended -confirm```.
2. Make new post ```hugo new posts/name-of-post.md```.
3. Run ```hugo``` to build static codes inside public directory for deploying on Netlify/Vercel.
4. Run ```hugo server``` to preview the site. 
5. Use GitHub Actions to deploy on GitHub Pages.
6. Update theme: Change [SamirPaulb/hugo-PaperMod](https://github.com/SamirPaulb/hugo-PaperMod) -> delete ```themes/PaperMod``` directory -> run ```git clone https://github.com/SamirPaulb/hugo-PaperMod themes/PaperMod --depth=1```

---

More instructions:
1. https://github.com/SamirPaulb/hugo-PaperMod
2. [Theme Basic Documentation](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-installation/)
3. [Theme Content Documentation](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-features/)
4. For local development first install [Chocolatey](https://docs.chocolatey.org/en-us/choco/setup#install-from-powershell-v3) as administrator then install hugo ```choco install hugo-extended -confirm```.
5. For deploying on Vercel add environment variable ```0.92.0``` [read more](https://github.com/vercel/vercel/discussions/5834#discussioncomment-2544322).
6. Use GitHub Actions for deploying on GitHub Pages.
7. For deploying on Netlify add netlify.toml and in config.toml give baseURL to Netlify domain.
8. Store resources in the ```/static/assets``` directory and refer it by ```/assets/File_Name```.
9. To deploy on Netlify/Vercel change the baseURL of config.toml to Netlify domain.
