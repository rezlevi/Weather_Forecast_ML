
## A rendszer célja
A rendszer célja Machine Learning segítségével megvalósítandó időjárás előrejelzés program lenne, ami egy előre megadott pl. csv file és az abban lévő adatokból próbál egy sémát találni és annak segítségével előre jelezni az időjárást. Ebben a rendszerben a megrendelő nem kérte, hogy legyen GUI vagy egyéb féle felhasználói felület, elég a Google Colab-os felület, futtatható kódblokkokkal. Felhasználókezelés nincs, aki hozzáfér a Colab füzethez, az tudja futtatni a programot.

## Projektterv
 

## Követelmények
- K01 Google Colab felületen kell készülnie a projektnek
- K02 Forrásfájlból történő beolvasás után időjárás előrejelzés
- K03 Machine Learning alkalmazása Tensorflow segítségével
- K04 Gráfok alkalmazása szemléltetésképpen

- Funkcionális követelmények ?
- Nem funkcionális követelmények ?
- Előírások ?

## Üzletifolyamatok modellje


## Implementációs terv


## Funkcionális terv
   
## Adatbázis terv leírása
A szoftver fejlesztése során egy hőmérsékleti adatokat tároló adatbázist fogunk használni.
Az adatbázis egy rekordja egy nap adatait tartalmazza, köztük a számunkra releváns napi átlag,
maximum, illetve minimum hőmérsékleteket.
Az adatbázis tartalmát nem módosítjuk, a fejlesztés során csak olvasni fogunk belőle.


## Tesztterv
A szoftver fejlesztésének végén történik a tesztelés, mely során a követelmény specifikáció
követelménylista pontjában szereplő elemek működését vizsgáljuk.
A tesztelés folyamatáról, illetve annak eredményéről részletes jegyzőkönyv készül.
A tesztelés során az egyes elemeken haladunk végig, ha valami nem működik kijavítjuk és 
újra azt a funkciót teszteljük egészen addig, míg nem lesz jó.
Csak ezután megyünk tovább. A folyamatot az alábbi ábra szemlélteti:

![Tesztelési terv](https://user-images.githubusercontent.com/113850216/201758430-fb3ea6f7-2838-4a23-b37b-035ed1159b01.png)

## Karbantartási terv
A rendszerünket természetesen nem engedjük el a fejlesztési folyamat legvégén sem.
A sikeres kiadást követően újabb verziók fejlesztése a céunk, melynek alapja
a korábbi rendszer.
Továbbá, ha egy megrendelőnknek teljesíthető modosítási igénye merülne fel,
igyekszünk úgy alakítani a rendszert, hogy az neki megfeleljen.


