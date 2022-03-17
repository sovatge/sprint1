# Sprint 1. HTML i CSS

# DESCRIPCIÓ

En aquesta pràctica hauràs de fer un Layout que ha de funcionar tant en escriptori, com mòbil i tauleta.

Tingues en compte les següents consideracions. Són errors habituals en els lliuraments:

- En general, mai li posem height a una capa, sinó que deixem que la capa s'adapti al seu contingut (si la capa no té contingut, li pots posar un height).
- La pàgina no hauria de tenir barra de scroll horitzontal (si et succeeix, hauràs d'esbrinar inspeccionant la pàgina que bloc és més ample que la pantalla del navegador).
- Dins d'un div sol haver-hi altres divs. Els divs tenen display:block per defecte. Això fa que es vagin col·locant de manera vertical. Per tant, sovint no és necessari especificar els següents estils per a un element per ser una cosa redundant:
    .element{ display:flex; flex-direction:column }
- En un div, per defecte l'ample és de la totalitat de la capa que embolica, així que normalment no serà necessari especificar width:100%

Lliurament per GitHub

- Crea un únic repositori de GitHub per als tres nivells, els podràs separar en carpetes.
Per exemple: nivell-1, nivell-2 i nivell-3.

- En els dos primers sprints hauràs de pujar el codi a GitHub perquè pugui veure'l el teu mentor.
A partír del sprint 3 hauràs de lliurar-lo per pull request, la manera en la qual els programadors lliuren el seu treball en les empreses.

- Si no tens clar del tot com pujar el teu projecte a git, al final d'aquest enunciat hi ha un "Annex I: Pujar el teu codi a git" que conté els passos que has de seguir.

# NIVELL 1

## EXERCICI 1

A partir del wireframe que t'aportem en format png, hauràs de fer la maquetació en format escriptori. És indiferents els colors escollits però si és molt important que facis l'estructura de caixes que t'indiquem.
L'ample màxim de la capa que contindrà tota la maquetació serà de 1200px (max-width:1200px).

<img width="1184" alt="ex1-flexbox-versio-escriptori" src="https://user-images.githubusercontent.com/11183610/158808471-153ab8a8-aece-4bb3-97c4-4768fe4a48ad.png">

## EXERCICI 2

Haurem de començar a preparar adaptació a diferents dispositius, pel que haurem de tenir clar el concepte de <a href="https://www.w3schools.com/css/css_rwd_mediaqueries.asp" target="_blank">Media Query</a>. Fixa't que hi ha canvi de distribució i color d'alguns elements.
Seguint amb el projecte anterior, fes la versió tauleta tal com indica la captura següent:

<img width="345" alt="ex2-flexbox-versio-tauleta" src="https://user-images.githubusercontent.com/11183610/158808726-c2eeb563-8d73-41f7-bedc-0a389a8e8516.png">

## EXERCICI 3

Com el cas anterior, ara hauràs de fer l'adaptació a versió Mobile.

<img width="205" alt="ex3-flexbox-versio-mobile" src="https://user-images.githubusercontent.com/11183610/158808933-02375edc-1cef-4873-94a9-ef9706a54308.png">

## Compte, abans de passar al nivell 2 verifica que has entès bé tots els exercicis del nivell 1. 

El nivell 2 i 3 són opcionals, l'important és aprendre els conceptes de cada sprint, si l'has copiat ràpid d'internet no té valor, ja que si passes així tots els sprints, hauràs treballat molt i après poc. 

# NIVELL 2

## EXERCICI 4

En aquesta part volem treballar la capçalera i el grafisme. Hauràs d'afegir icones i logotip, a més de fer una imatge de fons. Substitueix els quadrants respectius perquè la nova capçalera tingui l'aspecte d'aquest web de turisme al Japó:

![ex4-header-japo](https://user-images.githubusercontent.com/11183610/158809876-a9db7705-90a7-4787-a5c3-bd967675b937.png)

És important que tinguis en consideració el següent:

- Les opcions cliclables han de tenir efecte roll-over.
- Els media query creats a l'activitat anterior, s'ha de mantenir.
- El text "Disfruta..." és semitransparent.
- El logo i el fons de la capçalera, els tens adjuntat a l'activitat. La resta d'elements gràfics els hauràs de cercar i que siguin el més semblants possibles.
- Les icones del menú pots obtenir-los de <a href="https://fontawesome.com/" target="_blank">font-awesome</a>.

## EXERCICI 5

En aquest exercici hauràs d'afegir l'apartat dels articles seguint aquest grafisme:

![ex5-article-japo](https://user-images.githubusercontent.com/11183610/158810731-6a3da446-c961-496f-9e61-7515aabe0b1f.png)


A continuació tens una mostra de com quedaria la maquetació final de la pàgina.

![maqueta-final-nivell2](https://user-images.githubusercontent.com/11183610/158809454-a1e0beee-cdc1-45bf-947d-38d8fd7dcfc9.png)


# NIVELL 3

## EXERCICI 6

Enhorabona! has creat web completa, però com pots observar, és molt estàtica. Per a millorar l'experiència d'usuari, aplica sobre els elements principals de la web, títol i logo, una animació usant keyframes.

Ajuda: Tens un exemple molt senzill a partir del minut 22 d'aquest <a href="https://youtu.be/Cg1c6sy8Btk" target="_blank">video</a>.


## EXERCICI 7

Et veus capaç de fer el mateix treball però amb grid layout?. Doncs l'objectiu d'aquest treball és que utilitzis les propietats de grid layout per a fer tota l'estructura de la web i els seus diferents dispositius (sempre amb Media Query).

Si vols pots consultar el material opcional de grid layout que hi ha al campus.


# RECURSOS

El material te adjuntat els elements gràfics mínims, però hauràs de buscar imatges per a complementar-ho. Pots utilitzar recursos gratuïts com <a href="https://pixabay.com/es/" target="_blank">pixabay.com</a>.
