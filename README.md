# SADE-prototyyppi

Kevyt, staattinen mobiilinäkymää jäljittelevä SADE-demosovellus. Se ei tallenna oikeita käyttäjätietoja, ota yhteyttä ulkoisiin laitteisiin eikä toista äänitiedostoja — toiminnot ovat käyttöliittymäsimulaatioita esittelyä varten.

## Käyttö paikallisesti

Avaa `index.html` selaimessa. Erillistä asennusta tai palvelinta ei tarvita.

## Julkaisu GitLab Pagesiin

1. Luo GitLabissa uusi projekti ja lisää nämä tiedostot sen juureen.
2. Pushaa oletushaaraan (esimerkiksi `main`).
3. GitLab CI ajaa `.gitlab-ci.yml`-tiedoston ja julkaisee sivun Pages-palveluun.
4. Löydät osoitteen GitLab-projektin **Deploy > Pages** -kohdasta, kun pipeline on valmis.

Pipeline kopioi vain sivun tarvitsemat kolme tiedostoa `public`-hakemistoon. Sivusto toimii ilman npm-paketteja tai rakennusvaihetta.
