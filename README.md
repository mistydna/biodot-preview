# BIODOT Lab website

Static site for BIODOT Lab (Dr Ahmad Al Khleifat, King's College London), hosted on GitHub Pages.

Live at: https://al-khleifat-lab.github.io

## Pages
| File | Page |
|---|---|
| index.html | Home: intro, research themes, the main five team members, site directory |
| team.html | Full team, grouped, with the photo gallery at the bottom |
| research.html | The five research themes |
| publications.html | Papers |
| news.html | News |
| collaborators.html | Collaborators and funders |
| alumni.html | Former members |
| join-us.html | How to join |

## Editing
- People: copy an `<article class="member">` block. Put photos in `assets/people/` and add `<img src="assets/people/name.jpg" alt="Portrait of Name">` inside the `member-photo` div. Photos are cropped to a hexagon automatically, so square photos with the face centred work best.
- Gallery: put photos in `assets/gallery/` and copy the `<figure>` example on the Team page.
- The menu is repeated at the top of every page. If you add or rename a page, change it in all eight files.
- Colours and fonts are at the top of `css/style.css`.
