# Delhi Appliance Care website

Plain HTML and CSS. No build step, no frameworks.

## Pages

| File | Page |
|---|---|
| `index.html` | Home: photo hero, four service tiles, how it works, about, call band |
| `contact.html` | Contact |
| `privacy-policy.html`, `terms-and-conditions.html` | Legal pages |
| `home-appliance-repair.html` | Ad landing page. Not linked from any other page, and marked `noindex` so it stays out of Google search. Ads can still point to it. |
| `styles.css`, `images/` | Shared styles and photos |

## Replace the dummy details (find and replace across the folder)

| Find | Replace with |
|---|---|
| `Delhi Appliance Care` | Real business name |
| `+91 94110 78560` | Phone number as people should read it |
| `tel:+919411078560` | `tel:` plus the real number, digits only |
| `7 Days (7am - 11pm)` and `all 7 days, 7am - 11pm` | Real working hours |
| `00, Sample Street, Sample Area, Delhi NCR 110000` | Real address |

## Photos

All photos are in `images/` (webp). `ac-repair.webp` is a real AC repair photo; the other service tiles use general home-visit photos. Swap in real photos of your own technicians when you have them, keeping the file names.

Never add photos that show brand logos (for example an "LG Care" desk sign). They make the business look like the brand's own customer care, which is the most common reason Google Ads suspends repair advertisers (Misrepresentation policy).

## Ad page

To make more ad pages, copy `home-appliance-repair.html` under a new file name. Keep the line saying the business is independent and not the brand's official service centre, and never add a brand's logo, colours or the words "official", "authorised" or "customer care".
