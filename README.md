# symfony-form-3
Develery - próbafeladat

## Egy kapcsolat oldalt létrehozni egy képzeletbeli weboldalra, amelyen egy egyszerű contact form található. A formon a felhasználók kérdezni tudnak az oldaltól. A beérkező kérdéseket egy adatbázisba kell menteni.


### Az oldalnak semmi mást nem kell tartalmaznia, csak egy contact formot (kapcsolatfelvételi űrlapot). Az űrlapon a következő mezőknek kell megjelenniük:

Neved
- E-mail címed
- Üzenet szövege
- Küldés gomb

Mindhárom mező kötelezően kitöltendő legyen. A "Neved" és az "E-mail címed" mező egy
sornak megfelelő szöveget tartalmazzon, míg az "Üzenet szövege" mező egy bekezdésnyi
szövegnek adjon helyet. A "Küldés" gombra kattintva a következő két eset egyike valósuljon
meg:
Amennyiben minden mező helyesen van kitöltve: "Köszönjük szépen a kérdésedet.
Válaszunkkal hamarosan keresünk a megadott e-mail címen."
Amennyiben a három mező legalább egyike üresen van hagyva: "Hiba! Kérjük töltsd ki az
összes mezőt!"

A beküldött kérdések egy adatbázisba kerüljenek mentésre.
