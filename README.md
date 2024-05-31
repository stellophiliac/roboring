# roboring
a webring for robot-aligned beings! powered by [ringfairy](https://github.com/k3rs3d/ringfairy)

## join
1. choose a slug for your site (a unique identifier)

2. add the webring links to your site:

  ```html
  <a href="https://stellophiliac.github.io/roboring/YOUR_SLUG/previous"> <- </a>
  <a href="https://stellophiliac.github.io/roboring">roboring</a>
  <a href="https://stellophiliac.github.io/roboring/YOUR_SLUG/next"> -> </a>
  ```

  3. submit a pull request adding yourself to `websites.json`, or email me at `stel@disroot.org` and i'll add you manually.

  if you submit a PR, entries should have the **name** of your site, your **slug**, a short **description**, your **site link**, your **rss feed** (if applicable), and a **contact link** (such as an email or social media)

  here's an example entry:

  ```json
  {
    "name": "Example Website",
    "slug": "example",
    "about": "example site",
    "url": "https://example.com/",
    "rss": "https://example.com/index.xml",
    "owner": "person@example.com"
  }
  ```

