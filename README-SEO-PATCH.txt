
How to apply this SEO patch to your live site (https://padhaionline.github.io/padhaionline/):

1) In your GitHub repo 'padhaionline', upload/replace these files at the root:
   - robots.txt
   - sitemap.xml

2) Upload/replace this file in the assets/ folder:
   - assets/schema.json

3) Commit the changes. Then verify:
   - https://padhaionline.github.io/padhaionline/robots.txt  (should show the correct sitemap URL)
   - https://padhaionline.github.io/padhaionline/sitemap.xml (should list your pages)

4) Google Search Console:
   - Add property: https://padhaionline.github.io/padhaionline/
   - Use HTML tag verification and paste your token into the meta tag already present in:
       index.html, pages/courses.html, pages/notes.html, pages/worksheets.html,
       pages/pyqs.html, pages/tests.html, pages/contact.html
   - Submit your sitemap: https://padhaionline.github.io/padhaionline/sitemap.xml
