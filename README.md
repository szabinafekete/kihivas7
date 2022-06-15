# 1. nap / Feladat leírása!

Készítsd el az alap HTML dokumentum struktúrát (doctype, html, head, body).

Készíts egy H2-es szintű címsort „Június” felirattal.

Készíts egy 16 sorból és 7 oszlopból álló táblázatot. A fejlécben a hét napjai szerepeljenek. Az első sortól kezdve pedig minden harmadik sorba írd bele a megfelelő dátumot a megfelelő naphoz. Így minden számokat tartalmazó sor alatt 2 üres sor kell, hogy legyen. Ha szeretnéd, az első oszlopokba bele is írhatod a sorok számát, hogy lásd, jó helyre kerül-e az adat.

Eredményül ezt a nézetet kell kapnod:

![1 nap-1](https://user-images.githubusercontent.com/92752026/173111816-7c1aa313-5b61-466a-be37-0eddbbe3925e.png)

(a példában én csak a második és harmadik sorba írtam bele a sorjelzőt, viszont mindenhol megvannak az üres sorok)

# 2. nap / Feladat leírása!

Készíts 1px vastag, vonalas szegélyt, #dddddd színben a táblázat köré.

Állítsd be a szegélyek közötti rést 0-ra.

Az összes tartalmi cella (td) is kapjon ugyanolyan szegélyt, mint a táblázat. Majd ezeknek a celláknak vedd le a felső és alsó szegélyét.

Oldd meg, hogy csak a számokat tartalmazó cellák ismét megkapják az 1px vastag, vonalas szegélyt, #dddddd színben, viszont csak felül, és két oldalt.

A vasárnap oszlopában található számokat színezd #c0c0c0 színre.

Ezt az eredményt kell kapnod:

![2 nap-1](https://user-images.githubusercontent.com/92752026/173106893-3392baeb-c735-4e5f-8127-d9bcf50e46de.png)

# 3. nap / Feladat leírása!

A **táblázat** akkor igazán csinos, ha van egy kis sarokkerekítés. Kerekíts le a táblázat szegélyének sarkait 0.5vh értékkel, és növeld a táblázat szélességét 100%-ra.

A **fejlécek** kapjanak belső margót (padding), fent és lent 1vh és két oldalt 2vw értékben. Legyen a háttere #4c576b színű, és a betűk színét állítsd fehérre.

A bal szélső fejléc cella bal-felső sarka legyen lekerekítve 0.5vh értékben. A jobb szélső fejléc cellának pedig a jobb felső sarka kapjon ugyanilyen kerekítést.

A tartalmi cellák magassága legyen 2vh értékű. Legyen fent és lent 1.4vh és kétoldalt 3vh értékű belső margója. A betűk legyenek vastagok, és állítsd a színűket #777a7f kódra.

Ezt kell kapnod eredményül:

![3 nap-1](https://user-images.githubusercontent.com/92752026/173191397-0f0a07a1-7507-4895-a138-61d191975b57.png)

# 4. nap / Feladat leírása!

Az ikonok forrását itt találod:

nyitott lakat
zárt lakatleírása!

Ahhoz, hogy a tanfolyam sáv jól nézzen ki, össze kell vonni a cellákat és háttérszínnel kitölteni. Amennyi cellát összevonsz, annyit ki is kell törölni a HTML kódból.

Vond össze a második sor celláit június 1-től kezdve június 5-ig. Adj ennek az összevont cellának egy tnf, egy tnfColor és egy tnfBC1-es nevű osztályt. Értéknek tegyél a cellába egy <a> taget, aminek felirata: „Bevezetés a webprogramozásba” és mutasson a tanfolyam linkjére. Nyissa meg új ablakban az oldalt a kattintás során.

A fenti osztályokhoz állítsd be az alábbi stílusokat:
- **tnf**: sormagasság: 0.5vh és szegély kerekítés: 0.5vh
- **tnfColor**: a betűszín legyen #777a7f
- **tnfBC1**: a háttérszín legyen #e2cae2;

Eredményül ezt a kell, hogy kapd:
  
![4 nap-1](https://user-images.githubusercontent.com/92752026/173239336-60fe8bc2-a5fb-4c1d-bf9e-682d8feb4b43.png)
  
(link: [https://webprogramozoleszek.hu/elerheto-tanfolyamok/bevezetes-a-webprogramozasba-tanfolyam/](https://webprogramozoleszek.hu/elerheto-tanfolyamok/bevezetes-a-webprogramozasba-tanfolyam/))
  
# 5. nap / Feladat leírása!
  
Az első tanfolyam példája alapján készítsd el a többi tanfolyam megjelenítését is.

Ezt kell eredményül kapnod:

![5 nap-1](https://user-images.githubusercontent.com/92752026/173403424-01d1ca34-6fdc-4043-96a6-951bc7afa384.png)
  
Ha szeretnél bonyolítani a feladaton, akkor térj el a képtől, és

- a második tanfolyam kezdődjön 10-én pénteken, és tartson 12 napon át,
- a harmadik tanfolyam kezdődjön 14-én kedden, és tartson 7 napon át,
- a negyedik tanfolyam kezdődjön 23-án csütörtökön, és tartson 6 napon át.
  
Ha szeretnéd megoldani a nehezített feladatot, akkor ehhez ez az elvárt eredmény:

![5 nap_nehezites1](https://user-images.githubusercontent.com/92752026/173405647-03bd5570-f877-4c97-850f-73021cabcf21.png)

# 6. nap / Feladat leírása!

Az ikonok forrását itt találod:
  
- [nyitott lakat](https://www.devinexpertmode.hu/wp-content/uploads/2022/03/lock_open.png)
- [zárt lakat](https://www.devinexpertmode.hu/wp-content/uploads/2022/03/lock_closed.png)

Hozz létre egy tnfOpen nevű és egy tnfClose nevű CSS osztályt. Legyen mindkettőnek egy háttérképe, ami nem ismétlődik, és 15px-szer auto méretű. A tnfOpen háttérképének pozíciója legyen balról 0.5vw és fentről 1.2vh. A tnfClose háttérképének pozíciója legyen jobbról 0.5vw és fentről 1.2vh.

Ezt az eredményt kell kapnod:
  
![6 nap-1](https://user-images.githubusercontent.com/92752026/173637644-6ff513b5-1bf9-4a43-8c64-9ffbff415549.png)
  
# 7. nap / Feladat leírása!

Hozz létre egy média screen blokkot, ami azt vizsgálja, hogy max szélesség 600px.

Ebben a blokkban állítsd át a táblázat fejléc paddingját fent és lent 1vh-ra, és 2 oldalt 0.5vw-re. Legyen a betűméret itt 0.7em.

A táblázat cella magassága legyen 1vh, a paddingja pedig fent és lent legyen 1vh, két oldalt pedig 2vh.

A számokat tartalmazó cellák paddingja legyen lent és fent 0.3vh és két oldalt 0.

A tnfColor osztállyal rendelkező elemek betűmérete legyen 0.9em.

A lakat ikonok mérete legyen 12px-szer auto.

Az eredmény:
  
![7 nap_1-1](https://user-images.githubusercontent.com/92752026/173883680-9c7368ca-3374-44be-ac44-2603a7c2153a.png)
