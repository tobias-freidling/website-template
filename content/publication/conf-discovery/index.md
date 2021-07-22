---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Confidence in Causal Discovery with Linear Causal Models"
authors: ["David Strieder", "admin", "Stefan Haffner", "Mathias Drton"]
date: 2021-06-10
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "" #2021-07-30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "UAI 2021 (in press)"
publication_short: ""

abstract: "Structural causal models postulate noisy functionalrelations among a set of interacting variables. The causal structure underlying each such model is naturally represented by a directed graph whose edges indicate for each variable which other variables it causally depends upon. Under a number of different model assumptions, it has been shown that this causal graph and, thus also, causal effects are identifiable from mere observational data. For these models, practical algorithms have been devised to learn the graph. Moreover, when the graph is known, standard techniques may be used to give estimates and confidence intervals for causal effects. We argue, however, that a two-step method that first learns a graph and then treats the graph as known yields confidence intervals that are overly optimistic and can drastically fail to account for the uncertain causal structure. To address this issue we lay out a framework based on test inversion that allows us to give confidence regions for total causal effects that capture both sources of uncertainty: causal structure and numerical size of nonzero effects. Our ideas are developed in the context of bivariate linear causal models with homoscedastic errors, but as we exemplify they are generalizable to larger systems as well as other settings such as, in particular, linear non-Gaussian models."

# Summary. An optional shortened abstract.
summary: "We present a method to construct confidence intervals for causal effects in a linear structural equation model that accounts for the uncertainty stemming from the causal discovery of the DAG."

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2106.05694.pdf
url_code:
url_dataset:
url_poster: publication/conf-discovery/poster.pdf
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
