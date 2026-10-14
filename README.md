# Clear Panda – ιστοσελίδα

Στατική σελίδα (ένα αρχείο `index.html`), έτοιμη για GitHub Pages.

## Αρχεία
- `index.html` – η σελίδα
- `CNAME` – το custom domain
- `404.html`, `robots.txt`, `sitemap.xml`, `.nojekyll`
- `og.png` – (προαιρετικό) εικόνα 1200×630 για προεπισκόπηση σε Facebook/Viber/WhatsApp

## 1. Ανέβασμα στο GitHub
1. Φτιάξε νέο repository, π.χ. `clear-panda` (public).
2. Ανέβασε όλα τα αρχεία στο root (Add file → Upload files) και κάνε commit.
3. Settings → Pages → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.
4. Στο ίδιο μενού, στο **Custom domain** γράψε το domain σου και Save.
5. Όταν εκδοθεί το πιστοποιητικό, τσέκαρε **Enforce HTTPS**.

## 2. DNS (στον πάροχο του domain)
Για apex domain (`clearpanda.gr`) πρόσθεσε 4 εγγραφές **A**:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```
και για το `www` μία εγγραφή **CNAME** → `ΤΟ-USERNAME-ΣΟΥ.github.io`.

Η ενεργοποίηση DNS παίρνει από λίγα λεπτά έως 24 ώρες. Έλεγξε τις τρέχουσες IP στα επίσημα docs του GitHub Pages πριν τις βάλεις.

## 3. Μετά το ανέβασμα
- Ανέβασε `og.png` (1200×630) στο root.
- Πρόσθεσε το site στο Google Search Console και υπέβαλε το `sitemap.xml`.
- Ενημέρωσε το website στο προφίλ Google Business και στο Instagram.
