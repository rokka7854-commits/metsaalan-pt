# Metsäalan PT

Metsäkoneenkuljetuksen osaamisalan näytön arviointisovellus. Toteutus perustuu LogPT-sovellukseen (rokka7854-commits/logPT).

## Käyttö

1. Kirjaa näytön tunniste, näyttöpaikka, arvioijien nimet ja arviointipäivä.
2. Valitse näytössä arvioitavat tutkinnon osat.
3. Arvioi ammattitaitovaatimukset asteikolla 1–5 ja kirjaa huomiot.
4. Valitse jokaiselle tutkinnon osalle lopullinen arvosana, kirjaa allekirjoitukset ja kuittaa arvioinninoikaisumenettelyn tiedoksianto.
5. Tallenna tai jaa PDF. Päätä näyttö ja tyhjennä tiedot vasta tallentamisen jälkeen.

Keskiarvo on arvioijan apuna. Lopullinen arvosana valitaan erikseen, eikä sitä lasketa automaattisesti. Suoran tiedostojaon puuttuessa PDF ladataan laitteelle.

Sovellus toimii ilman kirjautumista. Tiedot tallentuvat vain käytetyn selaimen paikalliseen tallennustilaan. Älä tallenna opiskelijan nimeä, henkilötunnusta tai arkaluontoisia tietoja. Selaimen tietojen poistaminen poistaa myös keskeneräisen arvioinnin. Offline-käyttö ja asentaminen edellyttävät ensimmäistä avaamista verkossa HTTPS-osoitteessa.

## Sisältö

12 tutkinnon osaa ja niiden ammattitaitovaatimukset, ammattitaidon osoittamistavat sekä arviointiasteikko. Lähde: käyttäjän toimittama Metsäalan perustutkinto, OPH-7050-2025, voimaantulo 1.8.2026, PDF luotu 5.10.2026. Jäsennelty lähdeaineisto on tiedostossa `curriculum.json`.

- Kolme yhteistä pakollista osaa ja neljä vaihtoehtoista pakollista osaa.
- Viisi käyttäjän valitsemaa valinnaista osaa.
- Terminaalikoneenkuljettajan tutkinnon osa on perusteissa **Puuterminaalityöt**.
- **Koneelliset maanmuokkaus- ja metsähoitotyöt** on liitteen virallinen kirjoitusasu.
- Oppisopimusmerkinnät ja osien ryhmittely perustuvat käyttäjän rajaukseen. Sovellus ei tarkista koko tutkinnon muodostumissääntöjä.
- Paikallinen **Tuottava työskentely metsäkoneella** jätettiin käyttäjän pyynnöstä pois. Se lisätään myöhemmin hyväksyttyjen vaatimusten ja laajuuden perusteella.

## Julkaisu

Staattinen sovellus: GitHub Pages, `main`-haara, juurihakemisto. Ei rakennusvaihetta. Avaussivu on `index.html`. PDF-kirjasto ja kuvakkeet sisältyvät julkaisuun; ulkoisia palveluja ei tarvita arviointiin tai PDF:n luomiseen.
