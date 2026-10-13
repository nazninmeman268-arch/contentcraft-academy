# ContentCraft Academy — starter website

This is a responsive, static website starter for ContentCraft Academy.

## Included
- Home, About, Courses, Blog, Free Resources, and Contact pages
- Three sample blog article pages
- Responsive mobile navigation
- Basic page titles and meta descriptions
- Custom CSS design; no paid theme or external framework required

## Important before publishing
1. Review all wording and replace any placeholder or planned-course details with accurate information.
2. The contact form is a demo only. Connect it to a form service (for example, Google Forms or Formspree) before launch.
3. This starter is a static site. The sample blog pages are individual HTML files; a publishing CMS is **not configured yet**. A CMS and its authentication/publishing workflow must be set up before you can add posts through a dashboard from your phone.
4. No domain is required to preview the files locally. You can purchase and connect `contentcraftacademy.com` later.

## Preview
Open `index.html` in a browser.

## Deploy to Cloudflare Pages (static preview)
1. Create a Cloudflare account.
2. Create a GitHub repository and upload the contents of this folder.
3. In Cloudflare, open Workers & Pages, choose Create, then Pages, and connect the repository.
4. Use no build command and set the output directory to `/` (or follow Cloudflare's current static-site instructions).
5. Deploy to the provided `pages.dev` address.
6. Add your custom domain later from the Pages project when you own it; follow Cloudflare's current DNS instructions.

## Blog dashboard next
To publish posts from a phone without editing files, the site needs a CMS integration. Decap CMS is one possible open-source option, but it requires a compatible Git backend and authentication configuration. Do not assume the dashboard works until that integration is completed and tested.
