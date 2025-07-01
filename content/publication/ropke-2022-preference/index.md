---
title: Preference Communication in Multi-Objective Normal-Form Games

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Willem Röpke
- Diederik M. Roijers
- Ann Nowé
- Roxana Rădulescu
author_notes: []

date: '2022-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-07-01T07:44:02.508504Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '2'
publication: '*Neural Computing and Applications*'
publication_short: ''

doi: 10.1007/s00521-022-07533-6

abstract: We consider preference communication in two-player multi-objective normal-form
  games. In such games, the payoffs resulting from joint actions are vector-valued.
  Taking a utility-based approach, we assume there exists a utility function for each
  player which maps vectors to scalar utilities and consider agents that aim to maximise
  the utility of expected payoff vectors. As agents typically do not know their opponent's
  utility function or strategy, they must learn policies to interact with each other.
  Inspired by Stackelberg games, we introduce four novel preference communication
  protocols to aid agents in arriving at adequate solutions. Each protocol describes
  a specific approach for one agent to communicate preferences over their actions
  and how another agent responds. Additionally, to study when communication emerges,
  we introduce a communication protocol where agents must learn when to communicate.
  These protocols are subsequently evaluated on a set of five benchmark games against
  baseline agents that do not communicate. We find that preference communication can
  alter the learning process and lead to the emergence of cyclic policies which had
  not been previously observed in this setting. We further observe that the resulting
  policies can heavily depend on the characteristics of the game that is played. Lastly,
  we find that communication naturally emerges in both cooperative and self-interested
  settings.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
