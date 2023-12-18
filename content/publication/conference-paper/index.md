---
title: "Transfer Learning with Semi-Supervised Dataset Annotation for Birdcall Classification"
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Anthony Miyaguchi
- Nathan Zhong
- admin
- Chris Hayduk
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2023-06-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-29T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "CEUR Workshop Proceedings (CEUR-WS.org)"
publication_short: "CEUR"

abstract: We present working notes on transfer learning with semi-supervised dataset annotation for the BirdCLEF 2023 competition, focused on identifying African bird species in recorded soundscapes. Our approach utilizes existing off-the-shelf models, BirdNET and MixIT, to address representation and labeling challenges in the competition. We explore the embedding space learned by BirdNET and propose a process to derive an annotated dataset for supervised learning. Our experiments involve various models and feature engineering approaches to maximize performance on the competition leaderboard. The results demonstrate the effectiveness of our approach in classifying bird species and highlight the potential of transfer learning and semi-supervised dataset annotation in similar tasks.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["Transfer Learning", "Deep Learning", "Semi-Supervised", "BirdCLEF"]

# Display this page in the Featured widget?
# featured: true
publications: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ceur-ws.org/Vol-3497/paper-177.pdf'
url_code: 'https://github.com/dsgt-birdclef/birdclef-2023'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'BirdCLEF 2023'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

# slides: example

---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
