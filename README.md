This is an attempt to use [Netlify CMS](https://www.netlifycms.org/) framework within an RStudio Distill site deployed to GitHub Pages. The general goal is to pilot a team wiki that is version-controlled, yet editable by non-git users via the Netlify interface.

The site was initiated with 
```
distill::create_website(
  dir = "distill-with-netlifyCMS", 
  title = "My wiki",
  gh_pages = TRUE
)
```
