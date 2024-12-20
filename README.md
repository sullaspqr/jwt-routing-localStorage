# Példa JWT routing-gal és localStorage-al
Ebben a példában a korábbi JWT (Jason Web Token) -t kérhetünk a végponttól,
amit letárolunk localStorage-ban, majd minden route-unk hozzáfér ehhez a storage-hez
ahonnan lekérdezi a JWT-t és úgy küldi a végpontnak az Authorization: Bearer: token-t.

# Újdonságok
Készült új navbar, ami sm-nél collapsol és toggle-gombra bejön a navigáció.
Ehhez szükséges a bootstrap JS-része, amit az index.js-ben be kell hívni:
import 'bootstrap/dist/js/bootstrap.bundle.min.js';

# Logout script:
Logout-scriptet írtunk, ami kitörli a localStorage-ból a token-t.

# Issues:
Ebben a végpontban még nincs JWT érvénytartam implementálva.

# Backend végpontok:
[Backend végpont] (https://szallasjwt.sulla.hu/swagger)
