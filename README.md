# ☕ Kávé Sorsoló

Telefonra tervezett webapp: felviheted a kávéfőzési módszereidet, mindegyikhez egy vagy több receptet, a **Sorsolj!** gomb pedig kisorsol egy módszert, és hozzá egy receptet.

- Receptek: kávé, víz, őrlés, hőfok, idő (arány automatikusan), lépések, megjegyzés
- Időzítő, ha az idő perc:mp formában van megadva (pl. 3:00)
- Módszerek ki-/bekapcsolása a sorsoláshoz, „ne legyen ugyanaz, mint legutóbb”
- Előzmények statisztikával, JSON export/betöltés, nappali/éjszakai téma
- Telepíthető (PWA), offline is működik; az adatok csak a böngészőben tárolódnak

## Közzététel GitHub Pages-en

**Settings → Pages → Source: Deploy from a branch**, Branch: `main`, mappa: `/ (root)` → **Save**. Pár perc múlva elérhető: `https://<felhasználónév>.github.io/kave-sorsolo/`. Telefonon a böngésző menüjéből „Hozzáadás a kezdőképernyőhöz”.

Helyi kipróbálás: `python3 -m http.server 8000`, majd `http://localhost:8000`.
