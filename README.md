# absolute-directory-test
This is where I test different capabilities of github-pages. 
click [here](https://qanazoga.com/github-pages-testing) to go to the main page.

### What works and what doesn't
- [x] absolute directories: linking to `/` from a self-contained page (hosted from your docs folder of a repo etc.) will go to the root page of the website (hosted from `yourname.github.io`)
- [x] using a README.md (or any .md) as a page: works, kinda; you must link to the folder containing the .md file, linking to the .md itself will try to download it. The file must be named either `index.md` or `readme.md` or github will 404 you. If you have both an index and readme then `index.md` will take priority. 
- [x] forwarding: A page that immedietly forwards to another page works fine.
