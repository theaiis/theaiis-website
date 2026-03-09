# The AI Integration Specialists — theaiis.com
# Built March 2026

## Site Structure
```
/                   → index.html (main landing page)
/hello/             → About + video page (QR card destination)
/dynamicgm/         → Dynamic GM product placeholder
/assets/            → Images (add your files here)
```

## Assets Needed
Add these files to the /assets/ folder before deploying:
- `consultation.jpg` — the consultant + small business owner photo
- `storefront.jpg`   — the isometric circuit board storefront illustration

## Deploying to Netlify (5 minutes)
1. Go to netlify.com → Log in or sign up (free)
2. Click "Add new site" → "Deploy manually"
3. Zip the entire site folder
4. Drag and drop the zip onto the Netlify deploy page
5. Done — you'll get a random URL like funny-name-123.netlify.app

## Connecting theaiis.com to Netlify
1. In Netlify: Site settings → Domain management → Add custom domain
2. Type: theaiis.com
3. Netlify will give you nameservers or CNAME records
4. Go to Porkbun → DNS settings for theaiis.com
5. Point the records where Netlify tells you
6. SSL is automatic — Netlify handles it

## Later: Migrating to Home Server
When the home server is live (after March 26th):
- Point theaiis.com DNS to your home IP (Cloudflare tunnel recommended)
- Nginx Proxy Manager handles SSL termination
- Same site files, just different host
