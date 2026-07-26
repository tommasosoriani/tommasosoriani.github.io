# tommaso-soriani.github.io

Personal academic website for Tommaso Soriani, PhD candidate in Philosophy, University of Reading.

## How to publish this on GitHub Pages

1. Create a new GitHub repository named exactly: `tommaso-soriani.github.io`
   (replace with your GitHub username if different, e.g. `yourusername.github.io`)
2. Upload all the files in this folder to the root of that repository
   (index.html, research.html, publications.html, talks.html, teaching.html, cv.html,
   contact.html, style.css, and the assets/ folder).
3. Go to the repository's Settings > Pages.
4. Under "Build and deployment", set Source to "Deploy from a branch",
   Branch to "main" (or "master"), folder to "/ (root)". Save.
5. Wait 1-2 minutes. Your site will be live at:
   https://tommaso-soriani.github.io
   (or https://yourusername.github.io if you used a different repo name)

## To add your real CV PDF

Replace the placeholder link in cv.html with your actual CV PDF:
1. Add your CV PDF file to the assets/ folder, e.g. assets/CV_Tommaso_Soriani.pdf
2. The link in cv.html already points to assets/CV_Tommaso_Soriani.pdf

## To add a real headshot photo

Replace assets/headshot-placeholder.svg with a real photo (e.g. headshot.jpg),
then update the <img src="..."> reference in index.html accordingly.

## Editing content

All pages are plain HTML with a shared style.css. No build step, no dependencies.
Just edit the .html files directly and push changes to GitHub -- the live site
updates automatically within a minute or two.
