[Uploading README.txt…]()
RBRoca site for GitHub Pages
============================
Files
  index.html   the whole website
  news.json    drives the News tab (BIR Tax Reminder card, announcements, company activities)
  .nojekyll    tells GitHub Pages to serve the files as they are

Publish on GitHub Pages
  1. Create a GitHub repository and upload these three files to the main branch (root folder).
  2. Settings > Pages > Source: Deploy from a branch > Branch: main, folder: / (root) > Save.
  3. Your site appears at https://<user>.github.io/<repo>/ after a minute.

Edit the news
  Open news.json on GitHub, click the pencil icon, change the text, and commit.
  The News tab picks up the change on the next page load. Only https:// and in-site #links are shown.
  If news.json cannot be loaded, the page shows the copy built into index.html.

Notes
  - The contact, careers and payment forms send through FormSubmit to info@rbrocaconsultancy.com. The first submission sends a one-time activation email to that address.
  - GitHub Pages serves static files only, so the optional send-form.php (Hostinger) is not used there.
