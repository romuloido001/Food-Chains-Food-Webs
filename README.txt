CALINAN NATIONAL HIGH SCHOOL – FOOD CHAINS & FOOD WEBS INTERACTIVE LESSON

FILES
- index.html: complete standalone interactive lesson website.

PUBLISH TO GITHUB PAGES
1. Sign in to https://github.com/ and create a new repository.
2. Name it, for example: cnhs-food-chains-lesson
3. Set repository visibility to Public (if your school's policy permits).
4. Upload index.html to the ROOT of the repository. You may also upload this README.txt.
5. Open the repository's Settings tab.
6. Select Pages from the left menu.
7. Under Build and deployment, choose Deploy from a branch.
8. Select branch main and folder /(root), then click Save.
9. Wait for GitHub Pages to publish. The website URL will appear in the Pages section, usually https://YOUR-USERNAME.github.io/cnhs-food-chains-lesson/.

SCHOOL LOGO
The header currently uses a clearly marked CNHS LOGO text placeholder because no logo image file is included in this package. To add the official logo:
1. Add your official image file to the repository root and name it school-logo.png.
2. In index.html, find: <div class="logo" aria-label="School logo placeholder">CNHS<br>LOGO</div>
3. Replace that whole div with: <img class="logo" src="school-logo.png" alt="Calinan National High School logo">
4. In the CSS, change .logo styling as desired; for an image, add object-fit:contain; border-radius:50%; padding:4px.

IMPORTANT
- This is a static HTML website and works on GitHub Pages without a server or database.
- Learner answers and quiz results are not automatically sent to a teacher. Learners can download a text report and submit it using a teacher-approved method.
- Test the page on desktop and mobile before sharing it with learners.
