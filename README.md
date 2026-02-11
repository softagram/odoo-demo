# Demotarinat — Keskusvalmistajan myyntitapaaminen

Demo-ympäristö: **system.softagram.com** → Yritys: **Demonstration Oy**

Demon kokonaiskesto: ~50 minuuttia. Tarinat 1–7 muodostavat yhtenäisen ydinkulun (~35 min). Tarinat 8–12 ovat lisädemoja jotka voi näyttää ad hoc tarpeen mukaan (~15 min).

---

## YDINDEMOT (~35 min)

---

## Tarina 1: CRM — Liidit eivät huku enää (3 min)

**Valmistelu:** Avaa CRM → Putki (Pipeline)

**Ongelma:** *"Unohdamme soittaa potentiaalisille asiakkaille tai liidit hukkuvat sähköposteihin."*

**Kerronta:** *"Katsotaan ensin mistä kaikki alkaa — asiakashankinnasta. Tässä on myyntiputkenne yhdellä silmäyksellä."*

### Vaiheet

1. **Näytä Kanban-putkinäkymä** — 12 mahdollisuutta 4 vaiheessa
   - Uusi (4): Seinäjoki, Kokkola, Mikkeli, Pietarsaari
   - Hyväksytty (3): Vaasa, Lappeenranta, Turku
   - Ehdotus (3): Tampere, OYS, Helsinki
   - Voitettu (2): Jämsä sairaala 45 000 €, Kuopio päiväkoti 37 000 €
   - *"Koko myyntiputki yhdellä vilkaisulla. Jokainen liidi on seurannassa — kukaan ei unohdu."*

2. **Klikkaa OYS-mahdollisuutta** (Oulu University Hospital — 92 000 €)
   - Näytä: yhteyshenkilö, odotettu tuotto, todennäköisyys, takaraja, kuvaus
   - *"Kaikki oleellinen tieto yhdessä paikassa. Pekka Heikkinen, sähköinsinööri, tarjouskierros menossa, päätös maaliskuussa."*

3. **Näytä aktiviteetit-nappi**
   - *"Odoo muistuttaa automaattisesti — soitot, tapaamiset, seurannat. Mikään ei jää tekemättä."*

4. **Avainviesti:** *"Sähköpostiin tullut yhteydenotto ei huku — se on saman tien liidi CRM:ssä. Ja kun liidi etenee, koko tiimi näkee missä mennään."*

---

## Tarina 2: Asiakaskyselystä tarjoukseen (5 min)

**Valmistelu:** Avaa Myynti → Tarjoukset

**Ongelma:** *"Tarjousten tekeminen vie liikaa aikaa ja hinnastot ovat sekaisin."*

**Kerronta:** *"Sairaala ottaa yhteyttä uuden teho-osaston remontin tiimoilta. Katsotaan miten Odoo hoitaa tämän — kyselystä ammattimaiseen tarjoukseen."*

### Vaiheet

1. **Näytä olemassa oleva tarjous** `Tampere Office MDB` (SO #429 — luonnos)
   - Huomioi: asiakastiedot täyttyvät automaattisesti, tuoterivi hinnoitteluineen
   - *"Tässä on elävä tarjous odottamassa hyväksyntää."*

2. **Avaa vahvistettu myyntitilaus** `Hospital ICU Wing` (SO #427)
   - Näytä tilausrivi: **Hospital Power Center - ICU Grade** — 45 000 EUR
   - Huomioi: toimitustila, laskutustila, linkitetyt dokumentit
   - *"Kun asiakas vahvistaa, kaikki etenee automaattisesti."*

3. **Selaa tuotekatalogia** (Myynti → Tuotteet → hae "Power Center")
   - Näytä 6 valmista tuotetta oikeine hinnoitteluineen
   - Klikkaa **Hospital Power Center - ICU Grade** — näytä myyntihinta, kustannus, kategoria
   - *"Koko tuotekatalogi oikeilla hinnoilla — ei enää manuaalisia Excel-taulukoita."*

4. **Avainviesti:** *"Kyselystä ammattimaiseen tarjoukseen minuuteissa, ei päivissä. Ja hinnoittelu on aina oikein, koska se on yhteydessä todellisiin kustannuksiinne."*

---

## Tarina 3: Tilausohjautuva valmistus (Engineer-to-Order) (8 min)

**Valmistelu:** Avaa Valmistus → Tuoterakenteet

**Ongelma:** *"Tuotanto pysähtyy, koska jokin komponentti puuttuu."*

**Kerronta:** *"Sairaala hyväksyi tarjouksen. Katsotaan mitä tapahtuu valmistuspuolella — tämä on se kohta joka on teidän tyyppiselle työlle todella kiinnostava."*

### Vaiheet

1. **Avaa tuoterakenneluettelo** — 4 tuoterakennetta eri keskustyypeille
   - *"Jokaisella tuotetyypillä on oma tuoterakenteensa — resepti sen rakentamiseen."*

2. **Klikkaa BOM-HOSP-ICU** (Hospital Power Center - ICU Grade)
   - **Komponentit-välilehti:** Selaa 28 komponenttiriviä
     - Nosta esiin tiettyjä nimikkeitä: *"2x Erotusmuuntaja 8kVA, 2x Eristysvalvonta MEV-8, 18x MCB 16A johdonsuojakatkaisijaa..."*
     - *"Jokainen yksittäinen komponentti on seurannassa — erotusmuuntajasta riviliittimiin asti."*
   - **Työvaiheet-välilehti:** Näytä 5 valmistusvaihetta
     - Suunnittelu (24h) → Runkoasennus (12h) → Johdotus (32h) → Testaus (12h) → Loppukokoonpano (6h)
     - *"Jokaisella vaiheella on oma työkeskus ja tuntihinta. Tiedätte tarkalleen kuinka paljon työtä menee kuhunkin keskukseen."*

3. **Avaa Valmistus → Valmistustilaukset**
   - Näytä 4 valmistustilausta eri tiloissa:
     - MO/00001: Hospital ICU Wing — **vahvistettu** (linkitetty projektiin)
     - MO/00002: Kuopio Daycare — **vahvistettu** (linkitetty projektiin)
     - MO/00003: Varastotäydennys — **vahvistettu** (ei projektia, sisäinen)
     - MO/00004: Tampere Office — **luonnos** (odottaa tarjouksen hyväksyntää)
   - *"Koko tuotantoputki yhdellä silmäyksellä."*

4. **Klikkaa MO/00001** (Hospital ICU Wing)
   - Näytä: tuote, tuoterakenneviite, määrä, päivämäärät, projektilinkki
   - Komponentit-välilehti: kaikki tähän valmistukseen tarvittavat materiaalit
   - *"Kaikki on kytköksissä: myyntitilaus laukaisi valmistustilauksen, joka haki tuoterakenteen kaikkine komponentteineen."*

5. **Avainviesti:** *"Jokaisessa projektissa on täysi jäljitettävyys asiakastarjouksesta tarkkaan komponenttiluetteloon ja työtunteihin. Tiedätte katteenne aina ennen kuin aloitatte rakentamisen."*

---

## Tarina 4: Älykäs hankinta (5 min)

**Valmistelu:** Avaa Osto → Tilaukset

**Ongelma:** *"Ostamme tavaraa fiilispohjalta, emme datan perusteella."*

**Kerronta:** *"Valmistustilauksenne tarvitsevat komponentteja. Katsotaan miten Odoo hoitaa hankintapuolen."*

### Vaiheet

1. **Näytä ostotilausluettelo** — 4 ostotilausta eri toimittajille
   - 3 vahvistettua tilausta (Klinkmann, Intertrafo, PPO-Elektroniikka)
   - 1 tarjouspyyntöluonnos (Nordic Enclosures)
   - *"Jokaisella toimittajalla on oma tilaus heiltä tarvittavine komponentteineen."*

2. **Avaa ostotilaus Klinkmann Oy:lle** (vahvistettu)
   - Näytä 10 tilausriviä: johdonsuojakatkaisijat, kontaktorit, vikavirtasuojat
   - Huomioi määrät ja yksikköhinnat
   - *"Tässä on pääkomponenttitilauksenne Klinkmannille — kaikki katkaisijat ja suojalaitteet nykyiseen tuotantosarjaan."*

3. **Avaa ostotilaus Intertrafo Oy:lle** (vahvistettu)
   - 2x Erotusmuuntaja 8kVA + 1x 5kVA
   - *"Erikoiskomponentit erikoistoimittajilta — jokainen tietää tarkalleen mitä toimittaa."*

4. **Näytä tarjouspyyntö Nordic Enclosuresille** (luonnos)
   - *"Tämä on vielä tarjouspyyntövaiheessa — 4 jakelukeskuskaappia ja 3 asennuslevyä tuleville projekteille. Voitte vertailla tarjouksia ennen vahvistamista."*

5. **Navigoi toimittajan yhteystietoihin** (Yhteystiedot → hae "Klinkmann")
   - Näytä toimittajaprofiili
   - *"Jatkossa voitte asettaa automaattiset täydennyssäännöt — kun MCB 16A -varasto laskee alle 20 kappaleen, Odoo luo automaattisesti tarjouspyynnön Klinkmannille."*

6. **Avainviesti:** *"Kriittisiä komponentteja ei lopu koskaan kesken, kalliita nimikkeitä kuten erotusmuuntajia ei ylivarastoida. Järjestelmä tietää mitä tarvitsette, milloin tarvitsette, ja kuka toimittaa."*

---

## Tarina 5: Projektinhallinta ja tuntiseuranta (6 min)

**Valmistelu:** Avaa Projekti → Projektit

**Ongelmat:**
- *"Projektit ylittävät budjetin, emmekä tiedä miksi."*
- *"Työntekijöiden tunteja jää laskuttamatta."*

**Kerronta:** *"Teidän kokoiselle yritykselle jokaisen projektin tarkan kustannuksen tietäminen on ero kannattavuuden ja tappion välillä. Katsotaan miten Odoo seuraa tätä — mukaan lukien työtunnit."*

### Vaiheet

1. **Näytä projektiluettelo** — 3 projektia eri vaiheissa
   - Jämsän keskussairaala — Teho-osaston remontti
   - Kuopion päiväkoti — Uudisrakennus
   - Tampereen toimistokompleksi — Pääjakelu
   - *"Kolme aktiivista projektia, jokainen eri vaiheessa."*

2. **Klikkaa Jämsän sairaala -projektiin**
   - Näytä tehtäväluettelo vaiheineen:
     - ✅ Asiakasvaatimusten katselmointi — Valmis
     - ✅ Sähkösuunnittelu — Valmis
     - 🔄 Komponenttien hankinta — Käynnissä
     - ⏳ Keskuksen kokoonpano — Suunniteltu
     - ⏳ Tehdashyväksyntätesti (FAT) — Suunniteltu
     - ⏳ Toimitus ja käyttöönotto — Suunniteltu
   - *"Jokainen tiimin jäsen näkee tarkalleen missä projekti on menossa."*

3. **Avaa tehtävä "Sähkösuunnittelu"** → **Tuntiseuranta-välilehti**
   - Näytä kirjatut tunnit: *"Pääkaavion luonnostelu, piirikaaviot, eristysvalvontakaavio, johdotuskaaviot..."*
   - 8 tuntimerkintää, yhteensä ~44 tuntia suunnittelutyötä
   - *"Jokainen työtunti on kirjattu — mitä tehtiin, kuka teki, kuinka kauan kesti."*

4. **Avaa tehtävä "Komponenttien hankinta"** → Tuntiseuranta
   - 6 tuntimerkintää: tarjouspyynnöt, vertailu, tilaukset, seuranta
   - *"Hankintaan käytetty aika näkyy täällä — tiedätte tarkalleen paljonko myös epäsuoraa työtä menee kuhunkin projektiin."*

5. **Vaihda Kanban-näkymään**
   - Vedä ja pudota -visuaalisuus: tehtävät liikkuvat Uusi → Käynnissä → Valmis
   - *"Projektipäällikkö voi päivittää tilanteen yksinkertaisella raahauksella."*

6. **Yhdistä valmistukseen** — mainitse valmistustilauslinkki
   - *"Tämä projekti on linkitetty valmistustilaukseen MO/00001. Materiaalikustannukset tuoterakenteesta, työtunnit tuntiseurannasta — kaikki virtaa yhteen."*

7. **Avainviesti:** *"1,6 miljoonan liikevaihdolla ja tiukoilla katteilla jokaisen projektin tarkan kustannuksen — materiaalit plus työtunnit — tietäminen ei ole vapaaehtoista. Ja kun jokainen tunti kirjataan, yhtään laskutettavaa tuntia ei jää pöydälle."*

---

## Tarina 6: Moniprojektinäkymä ja liiketoiminnan kokonaiskuva (3 min)

**Valmistelu:** Avaa Valmistus → Valmistustilaukset (listanäkymä)

**Kerronta:** *"Otetaan askel taaksepäin ja katsotaan koko liiketoimintaa yhdellä silmäyksellä — tältä näyttää maanantaiaamunne Odoon kanssa."*

### Vaiheet

1. **Valmistustilausten listanäkymä**
   - 4 valmistustilausta: tuote, määrä, tila, alkuperä, takaraja
   - *"Koko tuotantoputkenne — mikä on vahvistettu, mikä käynnissä, mikä odottaa."*

2. **Vaihda projektiluetteloon**
   - 3 projektia alku-/loppupäivineen ja tiloineen
   - *"Projektisalkkune aikatauluineen."*

3. **Avaa Osto → Tilaukset**
   - 3 vahvistettua ostotilausta + 1 tarjouspyyntö = kokonaiskuva hankinnasta
   - *"Mitä on tilattu, mitä on tulossa, mitä pitää vielä pyytää tarjousta."*

4. **Avaa Myynti → Tilaukset**
   - 2 vahvistettua tilausta + 1 avoin tarjous
   - *"Myyntiputkenne — vahvistettu liikevaihto ja tulevat mahdollisuudet."*

5. **Avainviesti:** *"12 hengen yritys voi toimia samalla näkyvyydellä ja hallinnalla kuin paljon suurempi organisaatio. Exceleiden, sähköpostien ja puheluiden pyörittämisen sijaan — kaikki on yhdessä järjestelmässä."*

---

## Tarina 7: Tekoälyavustaja valmistuksessa (5 min)

**Valmistelu:** Avaa Valmistus → AI Assistant

**Kerronta:** *"Ja nyt jotain aidosti uutta — olemme integroineet Googlen Gemini-tekoälyn suoraan Odooseen. Tällä tekoälyavustajalla on reaaliaikainen pääsy kaikkeen valmistusdataanne."*

### Vaiheet

1. **Avaa Valmistus → AI Assistant** (avautuu dialogi)
   - *"Tämä on räätälöity moduli, jonka Softagram on rakentanut — se kytkee Odoon valmistusdatan suoraan Googlen Gemini-tekoälyyn."*

2. **Kysy:** "Give me an overview of our current manufacturing status. What's the biggest risk?"
   - Tekoäly vastaa kaikilla 4 valmistustilauksella, niiden tiloilla, takarajoilla ja tunnistaa riskit
   - *"Tekoäly näkee kaikki valmistustilauksenne, projektinne ja hankintanne — ja tunnistaa mihin pitää kiinnittää huomiota."*

3. **Kysy:** "Compare the material costs and margins of our Hospital ICU power center versus the Childcare Facility power center."
   - Tekoäly hakee tuoterakennekustannukset ja myyntihinnat, laskee katteet, ehdottaa optimointia
   - *"Tuoterakenteiden ja Exceleiden manuaalisen tutkimisen sijaan — kysykää vain tekoälyltä."*

4. **Kysy:** "What components do we need to order for our upcoming production? Which suppliers should we use?"
   - Tekoäly viittaa ostotilauksiin ja toimittajasuhteisiin
   - *"Tekoäly ymmärtää koko toimitusketjunne."*

5. **Avainviesti:** *"Tämä on toiminnanohjauksen tulevaisuus — tekoäly joka ymmärtää juuri teidän liiketoimintadataanne. Ei geneeristä ChatGPT:tä, vaan tekoäly joka on kytketty TEIDÄN tuotantotilauksiin, TEIDÄN tuoterakenteisiin, TEIDÄN projekteihin. Ja tämä pyörii avoimen lähdekoodin Community-versiolla."*

---

## LISÄDEMOT — näytä tarpeen mukaan (~15 min)

*Nämä tarinat voi nostaa esiin ad hoc, jos asiakas on kiinnostunut kyseisestä alueesta.*

---

## Tarina 8: Verkkokauppa ja nettisivut (4 min)

**Valmistelu:** Avaa system.softagram.com/shop uudessa välilehdessä

**Ongelmat:**
- *"Verkkokaupan tilaukset pitää naputella käsin toiminnanohjaukseen."*
- *"Nettisivut ovat vanhentuneet, koska niiden päivitys on vaikeaa."*

**Kerronta:** *"Entä jos asiakkaanne voisi selata tuotekataalogianne ja tilata suoraan verkosta?"*

### Vaiheet

1. **Avaa /shop** — näytä julkaistut tuotteet
   - 6 sähkökeskusta verkkokaupassa: Hospital Standard, ICU Grade, Childcare, Industrial, HVAC, MDB 630A
   - *"Tuotekatalogi on verkossa — suomenkielisillä kuvauksilla ja oikeilla hinnoilla."*

2. **Klikkaa Hospital Power Center - ICU Grade**
   - Näytä tuotesivu: hinta 45 000 €, kuvaus, lisää koriin -nappi
   - *"Asiakas voi tutustua tuotteeseen ja pyytää tarjouksen — tai tilata suoraan."*

3. **Näytä sivueditori** (klikkaa "Muokkaa" yläpalkista)
   - Vedä ja pudota -lohkot: tekstiä, kuvia, painikkeita
   - *"Sivujen päivittäminen ei vaadi koodausta — drag & drop. Markkinointitiimi voi itse pitää sivut ajan tasalla."*

4. **Ydinviesti:** *"Verkkokauppatilaus syntyy automaattisesti myyntitilauksena Odoossa — sama varasto, sama laskutus. Ei käsin naputtelua."*

---

## Tarina 9: Sähköpostimarkkinointi (3 min)

**Valmistelu:** Avaa Sähköpostimarkkinointi → Postitukset

**Ongelma:** *"Markkinointiviestit lähtevät manuaalisesti Outlookista."*

**Kerronta:** *"Miten tavoitatte tehokkaasti potentiaaliset asiakkaat? Ei yksittäisillä sähköposteilla — vaan kohdistetulla markkinoinnilla."*

### Vaiheet

1. **Näytä postitusluettelo** — 3 kampanjaa
   - "Uusi ICU-luokan sähkökeskus" — **lähetetty** (2 viikkoa sitten)
   - "Päiväkotien sähköturvallisuus — uudet RCBO-vaatimukset" — **lähetetty** (viikko sitten)
   - "Automaatiokeskukset teollisuuteen" — **luonnos** (odottaa lähetystä)
   - *"Kolme kampanjaa eri kohderyhmille — sairaalat, kunnat, teollisuus."*

2. **Avaa ICU-keskus -kampanja**
   - Näytä sähköpostin sisältö: tuotteen esittely, ominaisuudet, toimintakutsu
   - *"Ammattimainen viesti joka lähti kerralla kaikille sairaala-alan päättäjille."*

3. **Avaa Sähköpostimarkkinointi → Postituslistat**
   - 4 listaa: Sairaalat (6 kontaktia), Teollisuus (5), Kunnat (5), Uutiskirje (9)
   - *"Kohderyhmät segmentoitu valmiiksi — eri viesti eri yleisölle."*

4. **Näytä luonnoskampanja** "Automaatiokeskukset teollisuuteen"
   - *"Tämä odottaa lähetystä. Ajoitatte julkaisun kun uusi tuote on valmis — yhdellä klikillä kaikille teollisuusasiakkaille."*

5. **Avainviesti:** *"Outlookista ei lähde kohdennettua markkinointia sadoille vastaanottajille. Odoossa luotte kampanjan, valitsette kohderyhmän, ja järjestelmä hoitaa loput — ja seuraa kuka avasi ja kuka klikkasi."*

---

## Tarina 10: Kassapääte — myymälä ja komponenttimyynti (2 min)

**Valmistelu:** Avaa Kassapääte (Point of Sale)

**Ongelma:** *"Kivijalkakaupan ja verkkokaupan varastosaldot eivät täsmää."*

**Kerronta:** *"Jos myyt komponentteja myös suoraan varastolta — esimerkiksi tuttu asentaja hakee pikaisesti johdonsuojakatkaisijoita — tarvitset kassajärjestelmän."*

### Vaiheet

1. **Avaa Kassapääte** → "Myymälä — Komponenttimyynti"
   - Näytä kassanäkymä
   - *"Tässä on kassanäkymä. Tuotteet ovat samat kuin varastossa ja verkkokaupassa."*

2. **Lisää tuote kassalle** — hae esim. "MCB 16A"
   - Näytä hinta, määrä, kokonaissumma
   - *"Myyt tiskiltä — ja varastosaldo päivittyy heti. Sama tuote, sama varasto."*

3. **Avainviesti:** *"Yksi varasto — myit sitten verkosta, tiskiltä tai tuotantoon. Saldot täsmäävät aina, koska kaikki on samassa järjestelmässä."*

---

## Tarina 11: Laskutus ja rahatilanne (3 min)

**Valmistelu:** Avaa Laskutus → Asiakaslaskut

**Ongelmat:**
- *"Asiakkaat maksavat myöhässä, koska laskujen lähetys viivästyy."*
- *"En tiedä yrityksen tarkkaa rahatilannetta ennen kuin kirjanpitäjä lähettää raportin."*

**Kerronta:** *"Katsotaan miten laskutus ja rahavirta pysyvät hallinnassa."*

### Vaiheet

1. **Näytä laskuluettelo** — 282 laskua
   - Valtaosa tilassa "Kirjattu" (posted)
   - *"Kaikki laskut yhdessä paikassa — tilat, eräpäivät, maksusuoritukset."*

2. **Näytä laskun luonti myyntitilauksesta**
   - Avaa vahvistettu SO → klikkaa "Luo lasku"
   - *"Tilaus vahvistetaan, tavara toimitetaan, lasku syntyy automaattisesti. Ei viivettä — asiakas saa laskun heti toimituksen jälkeen."*

3. **Avaa Laskutus → Dashboard** (yleiskatsaus)
   - Näytä avoimet saatavat, maksetut, myöhässä olevat
   - *"Tässä on reaaliaikainen tilannekuva: kuinka paljon rahaa on tulossa, kuinka paljon on myöhässä, mikä on kassatilanne."*

4. **Avainviesti:** *"Ei tarvitse odottaa kirjanpitäjän kuukausiraporttia. Rahatilanne on aina ajan tasalla — ja laskut lähtevät heti kun työ on tehty."*

---

## Tarina 12: Kulujen hallinta ja ajoneuvojen seuranta (2 min)

**Valmistelu:** Avaa Kulut → Omat kulut

**Ongelma:** *"Kuitit ovat rypistyneinä taskuissa ja kulukorvaukset myöhässä."*

**Kerronta:** *"Vilkaistaan vielä taustatoimintoja — nekin ovat integroituja."*

### Vaiheet

1. **Näytä kululuettelo** — ~977 kulukirjausta
   - Hotellit, lennot, ateriat, taksit, konferenssimaksut
   - *"Asennustiimenne matkustaa sairaaloihin — kaikki kulut kirjataan ja seurataan täällä."*

2. **Avaa Kalusto → Ajoneuvot**
   - Näytä yrityksen ajoneuvot (60 kpl) kilometriseurantoineen
   - *"Huoltoautot asiakaskäynneille, matkamittarilokit ja huoltojen aikataulutus."*

3. **Avainviesti:** *"Ei enää paperikuitteja, ei enää kilometritaulukoita. Kaikki virtaa samaan kirjanpitojärjestelmään."*

---

## Yhteenveto (2 min)

**Kerronta:** *"Tiivistetään mitä näimme tänään."*

**Ydintoiminnot:**
1. **CRM** → Myyntiputki jossa liidit eivät huku — 12 mahdollisuutta seurannassa
2. **Myynti** → Ammattimaiset tarjoukset oikealla tuotehinnoittelulla
3. **Valmistus** → Tuoterakenteet jokaisella komponentilla, työvaiheet työkustannuksineen
4. **Hankinta** → Toimittajahallinta ja automaattinen tilausmahdollisuus
5. **Projektit + Tuntiseuranta** → Tehtäväseuranta, työtunnit ja kustannukset yhdessä
6. **Tekoälyavustaja** → Gemini-pohjainen valmistuksen älykkyys suoraan Odoossa

**Lisätoiminnot:**
7. **Verkkokauppa** → Tuotekatalogi verkossa, tilaukset virtaavat suoraan Odooseen
8. **Sähköpostimarkkinointi** → Kohdistetut kampanjat eri asiakassegmenteille
9. **Kassapääte** → Tiskimyynti samasta varastosta
10. **Laskutus** → Automaattinen laskutusketju, reaaliaikainen kassatilanne
11. **Kulut ja kalusto** → Kulukorvaukset ja ajoneuvojen seuranta integroituna

*"Kaikki tämä pyörii Odoo 19 Community Editionilla — avoin lähdekoodi, ei käyttäjäkohtaisia lisenssimaksuja. Ja tekoälyintegraatio? Se on räätälöity moduli, jonka Softagram rakentaa teille — kytketty TEIDÄN dataanne, ei geneeristä tekoälyä."*

*"Keskusvalmistajalle joka tekee tilausohjautuvaa työtä, ydinviesti on tämä: jokaisella projektilla on uniikki tuoterakenne, uniikit komponentit ja uniikki kustannusrakenne. Odoo seuraa kaikkea tätä ensimmäisestä asiakaskyselystä lopputoimitukseen. Tiedätte aina katteenne — ja nyt voitte kysyä niistä tekoälyltä."*

---

## Enterprise-ominaisuudet (mainitse tarvittaessa)

Nämä ongelmat ratkeaisivat Odoo Enterprise -versiolla:

| Ongelma | Enterprise-sovellus | Mitä kertoa |
|---------|-------------------|-------------|
| *"Laskutan kuukausisopimuksia manuaalisesti"* | **Subscriptions** | Toistuvat laskut automaattisesti — kuukausi-, vuosi-, tai räätälöidyllä jaksotuksella |
| *"Sopimusten allekirjoitus vaatii tulostamista"* | **Sign** | Sähköinen allekirjoitus suoraan Odoosta — tarjous → allekirjoitus → vahvistus |
| *"Työntekijät eivät tiedä mitä vaihetta työstää"* | **Shop Floor** | Tablettinäkymä tehtaalle — työntekijä näkee oman vaiheensa ja kuittaa valmiiksi |
| *"Huoltoautot ajavat turhia reittejä"* | **Field Service** | Kenttätyöt kartalla, reittioptimointi, mobiilisovellus asentajille |
| *"Asiakaspalvelu sähköpostissa kaaosta"* | **Helpdesk** | Tikettijärjestelmä — sähköposti → tiketti → priorisointi → vastaus SLA-ajassa |

*"Nämä ovat saatavilla Enterprise-lisenssillä. Community-versio kattaa ydinliiketoiminnan, ja Enterprise laajentaa sitä näillä erikoisalueilla."*

---

## Pikaopas: Mistä löydät asiat

| Mitä näytetään | Navigointipolku |
|---------------|----------------|
| CRM-putki | CRM → Putki |
| Tarjoukset | Myynti → Tarjoukset |
| Vahvistetut tilaukset | Myynti → Tilaukset |
| Tuotteet | Myynti → Tuotteet tai Varasto → Tuotteet |
| Tuoterakenteet | Valmistus → Tuoterakenteet |
| Valmistustilaukset | Valmistus → Valmistustilaukset |
| Työkeskukset | Valmistus → Asetukset → Työkeskukset |
| Ostotilaukset | Osto → Tilaukset |
| Tarjouspyynnöt | Osto → Tilaukset (tila = Tarjouspyyntö) |
| Projektit | Projekti → Projektit |
| Tehtävät + tunnit | Projekti → Kaikki tehtävät → Tuntiseuranta-välilehti |
| Tuntiseuranta | Tuntiseuranta → Omat tuntiseurannat |
| Kulut | Kulut → Omat kulut |
| Kalusto | Kalusto → Ajoneuvot |
| Tekoälyavustaja | Valmistus → AI Assistant |
| Verkkokauppa | /shop tai Verkkosivu → Verkkokauppa |
| Sivueditori | Verkkosivu → avaa sivu → Muokkaa |
| Sähköpostimarkkinointi | Sähköpostimarkkinointi → Postitukset |
| Postituslistat | Sähköpostimarkkinointi → Postituslistat |
| Kassapääte | Kassapääte → Dashboard |
| Asiakaslaskut | Laskutus → Asiakaslaskut |
| Kirjanpidon yleiskatsaus | Laskutus → Dashboard |
| Toimittajat | Yhteystiedot → hae toimittaja |
| Asiakkaat | Yhteystiedot → hae asiakas |
