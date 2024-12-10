# Házi feladat (pandas 2. kiadás)

1) Ugyanazt az adatbázist használjuk még mindig, amit az órán és az előző házi feladatban.
2) Ehhez a házi feladathoz sem lesznek tesztek, a megoldásokat a README.md fájl szerkesztésével tudjátok majd megadni. A válaszokhoz tartozó kódot töltsétek fel a githubra (de az adatot semmiképpen ne tegyétek fel). Egyes kérdéseknél csak a kód beadása is elég.
3) Az egyes kérdéseknél a 7 vagy 8 (vagy 77 vagy 88) a nem tudja, nem válaszol kategóriákat rögzíti. Ezeket a minimum és maximum számolásnál ne vegyétek figyelembe

### Válaszoljátok meg a következő kérdéseket:

Készítsünk tipológiát az általános emberekbe vetett bizalom kapcsán. A `ppltrst` változó azt mutatja meg, hogy a kérdezett szerint mennyire lehet megbízni az emberekben, míg a `pplfair` változó azt, hogy a kérdezett szerint az emberek mennyire becsületesek. 
- Készíts mind a kettő változóból egy-egy 2 kategóriás változót, ahol az 5 vagy az alatti értékek 0-ás, az afeletti értékek 1-es értéket kapnak. 
- A két változó alapján hozz létre egy tipológiát (azaz az új változónak 4 kategóriája lesz, aki mind a kettőre 0-t adott, mind a kettőre 1-et, és a két vegyes opció).
- Vizsgáld meg, hogy az egyes csoportokban mekkora az átlag életkor (`agea`) [4 szám]
- Készíts egy pivot táblát, amiben ezt a változót valamint a nemet (`gndr`) használod. Vizsgáld meg, hogy hogyan alakul a demokráciával való elégedettség átlagosan a nemek és bizalmi tipológia mentén (`stfdem`).

Ábrázolás:
- Készítsetek egy ábrát, ami azt mutatja be, hogy mennyire boldogok általában az emberek (`happy`). Válasszatok olyan ábrázolási módot, ami szerintetek a legszemléletesebb, ha szeretnétek, akkor bevonhattok más változót is az ábrázolásba.

Adatbázis kiegészítés:
- Szűkítsétek le az adatbázist csak agea, eduyrs, ppltrst, pplfair, cntry változókra.
- Hozz létre egy új sort, amiben a saját válaszaidat tárolod: a korod egész számban (`agea`), oktatásban eltöltött évek száma (`eduyrs`), a tipológiához felhasznált 2 változó (mind a kettő 0-10-ig terjedő skálán, ahol a 0 a bizalmatlanságot jelöli míg a 10 azt hogy a legtöbb emberben meg lehet bízni és ugyanez a becsületességgel), ország változó (`cntry`). Illeszétek ezt a sort a táblázathoz úgy, hogy a megfelelő válaszok a megfelelő oszlopba kerüljenek. 
