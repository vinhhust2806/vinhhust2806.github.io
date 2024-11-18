---
title: 'Polyp-SES: Automatic Polyp Segmentation with Self-Enriched Semantic Model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Thanh Hoang Son Vo
  - Sae Ryung Kang
  - Soo Hyung Kim

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-12-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-20T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Asian Conference on Computer Vision*
publication_short: In *ACCV*

abstract:   Automatic polyp segmentation is crucial for effective diagnosis and treatment in colonoscopy images. Traditional methods encounter significant challenges in accurately delineating polyps due to limitations in feature representation and the handling of variability in polyp appear ance. Deep learning techniques, including CNN and Transformer-based methods, have been explored to improve polyp segmentation accuracy. However, existing approaches often neglect additional semantics, restricting their ability to acquire adequate contexts of polyps in colonoscopy images. In this paper, we propose an innovative method named “Auto matic Polyp Segmentation with Self-Enriched Semantic Model” to address these limitations. First, we extract a sequence of features from an input image and decode high-level features to generate an initial segmen tation mask. Using the proposed self-enriched semantic module, we query potential semantics and augment deep features with additional semantics, thereby aiding the model in understanding context more effectively. Extensive experiments show superior segmentation performance of the proposed method against state-of-the-art polyp segmentation baselines across five polyp benchmarks in both superior learning and generalization capabilities.

# Summary. An optional shortened abstract.
summary: ''

tags:
  - Medical Image Analysis

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2410.01210'
url_code: 'https://github.com/vinhhust2806/Polyp-SES'
url_dataset: 'https://drive.google.com/file/d/1pFxb9NbM8mj_rlSawTlcXG1OdVGAbRQC/view'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://arxiv.org/pdf/2410.01210'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
