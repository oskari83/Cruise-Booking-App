## Aineopintojen harjoitustyö: Tietokantasovellus

Sovellukseni on nettisivu, jonka kautta käyttäjä voi varata fiktiivisiä risteilymatkoja (ks. https://www.vikingline.fi/ tai https://www.tallink.com/). 

## Cruise-booking-app

Sovelluksessa näkyy eri risteilymatkoja, joita käyttäjä voi tarkastella. Käyttäjä voi varata haluamansa matkan, jolloin hän valitsee eri vaihtoehtoja (ruokailu, hytti, auto), sekä täyttää matkustajista tarvittavat tiedot (nimet, syntymäaika, sähköposti), sekä lisää muita tietoja. Tämä on peruskäyttäjän keskeinen toiminnallisuus, kun taas sovelluksen ylläpitäjä voi tarkastella jokaisen matkan varaustilannetta, sekä jokaisen yksittäisen varauksen tietoja. Normaalikäyttäjä voi kirjautua sovellukseen, tai varatessaan ensimmäistä matkaa luoda uuden käyttäjätunnuksen. 

Sovelluksen ominaisuuksia:
- käyttäjä voi kirjautua sisään tai luoda käyttäjätunnuksen home-näkymästä
- käyttäjä voi selata eri matkoja home-näkymästä
- käyttäjä voi klikata matkaa joka vie hänet siihen kuuluvaan näkymään
- matka-näkymässä käyttäjä voi tehdä varauksen, jolloin hän valitsee eri vaihtoehtoja (ruokailu, hytti, auto), sekä täyttää matkustajista tarvittavat tiedot (nimet, syntymäaika, sähköposti), sekä lisää muita tietoja
- matka-näkymässä tehdessään varausta käyttäjä voi myös rekisteröityä jos hän ei ole vielä kirjautunut sisään
- tehtyään varauksen (ja ollessaan sisäänkirjautuneena) käyttäjä voi tarkastella varauksiaan profiili-näkymässä
- ylläpitäjä voi tarkastella risteilymatkoja admin-näkymässään
- ylläpitäjä voi lisätä uusia risteilymatkoja admin-näkymässään
- ylläpitäjä voi tarkastella risteilymatkan varaustilannetta näkymässään, sekä tarkastella yksittäisiä varauksia, ja niihin liittyviä käyttäjiä

## Ohjelman asennus
Suorita seuraava komento: 
pip install -r requirements.txt