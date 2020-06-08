## Abstract
The SUAVs were initially designed for military applications, but they are becoming more popular in civil applications due to technological advancements in cost reduction and miniaturization. However, SUAVs’ autonomy and maneuverability are limited because of its  kinematics and low energy capacity constraints. Therefore, these limitations must be taking into account when planning feasible trajectories for these vehicles. The trajectories must attend the SUAVs’ kinematic constraints, visit multiple waypoints and have minimized length. Currently methods are capable of finding feasible trajectories for SUAVs that attend the kinematic constrains, but cannot minimize length, or visit multiple waypoints. This dissertation introduces TEvol, an algorithm capable of finding feasible trajectories that attend to kinematic constraints of curvature, torsion and climbing for multiple waypoints with minimized length. Furthermore, TEvol can also consider kinematic constraints of velocity and load factor based on the specific SUAVs’ V-n diagram, which can protect the vehicle from structural failure and stall. The trajectories are modeled as Bézier curves and optimized by non-dominated sorting genetic algorithm (NSGAII). The results indicate that the algorithm is capable of finding trajectories with minimized length that visit multiple waypoints and attend to the kinematic constraints of curvature, torsion and climbing, or velocity and load factor, and both simultaneously. The algorithm found valid trajectories for 81.66\% of the experiments executed.

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/sergiopolimante/TEvol/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
<iframe width="560" height="315" src="https://www.youtube.com/embed/6_Rov8Kf96U" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/sergiopolimante/TEvol/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
