# BakeIT
Brandon Tsegai, Cecilia Karlsson & Tommy Kärnström<br>
Repostory [link](https://github.com/tomkaar/BakeIT)<br>
Github Pages [Link](https://tomkaar.github.io/BakeIT/)<br>
Trello [Link](https://trello.com/b/I8tPOZPr/bakeit)


## Om Bake IT
Med mål om att ta ett klassiskt svenskt koncept utomlands - fika - och få in mer personlighet i vårt arbetssätt istället för det hårda rakt-på men ändå behålla ett professionellt beteende. Vårt mål är att hjälpa existerande företag - stora och små - att modernisera eller ändra företagets image och hemsida. <br>
Välkommen in på en fika!  

## Arbetsmetod
Vi har använt trello för att hålla koll på kommande, pågående samt klara arbetsuppgifter - på detta vis har alla alltid haft koll på vad som händer i projektet. Med stort fokus på kommunikation mellan medlemmarna har arbetet gått framåt i stadig takt.<br>

Med uppdelning utav undersidor att göra hade alla något att göra, en sida var. Tillsammans gjorde vi en bas med variabler, mixins och färdiggjorda moduler så det var enkelt att skapa sina egna sidor och få sidorna att se likadana ut. <br>

Vi försökte att spendera så mycket tid i klassrummet som möjligt, varje gång vi gjorde någon större ändring som påverkade varandras sidor så var vi noga med att säga till varandra och pusha till github för att undvika merge konflikter så mycket som möjligt. <br>

Github har använts men på grund av sättet vi arbetat på så har inte branches varit super användbart, och användes främst i början.


## Mockup vs Verklighet
Vi var väldigt nöjda med hur resultatet på vår mock-up såg ut, och valde att inte implementera många ändringar på vår slutgiltiga produkt, utan utgick från vår färdiga mock-up till stor grad. Samtliga ändringar vi gjorde gjordes genom konsensus och en väluttänkt anledning.


## Tillgänglighetsanpassad
Vi misslyckas med testet främst angående kontrast - utöver de partier där vi har en bakgrundsbild (som den inte kan tolka) klagar den även på de mer färgglada partierna. Denna error motiverar vi sådan att hade vi följt deras önskemål hade det blivit mer eller mindre svart på vitt. Vi anser även att denna error är ‘okej’ i och med att skärmläsaren (ChromeVox) kunde läsa texten åt en. <br>

Den klagar även på de små knapparna vi har vid den fejkade slidern (reviews), detta ignorerar vi då i ett professionellt projekt hade man antagligen inte kodat detta som knappar, utan kanske mer som bilder, därav det tomma värdet som den klagar på. Samma angår BakeIT iconen, som också anses ‘tom’ och med dubbel länkandet till home - känns som en standard grej att kunna klicka på logo:n för att komma till huvudsidan.<br>

För dessa test använde vi oss utav Wave extension till Chrome, Axe Accessibility extension till Chrome samt ChromeVox för skärmläsning, även denna en extension.  


## Sammanfattning
Med god kommunikation och stor tid som spenderades att koda sida vid sida finns det många lärdomar att hämta ifrån vårt arbete. Genom att alla medlemmar var med i samtliga delar av sidans uppbyggnad lämnade det oss med stor frihet att självständigt göra ändringar vart det än krävdes i källkoden.

Tydligt strukturerad kod bidrog till att problemlösning blev enklare, då det lämnade oss med många verktyg att använda. Genom att ha tillgång till samma variabler och mixins är vår sida även lätt att underhålla då samtliga delar av den använder sig av samma styling, vilket innebär att man kan göra många ändringar på sidan med endast några få ändringar i den slutgiltiga CSS-koden.

Vi var även väldigt konsekventa med att ses och arbeta på projektet utan att låta alltför lång tid gå emellan våra gruppsessioner, och på så vis effektivisera tiden man jobbade på egen hand, då man inte behövde oroa sig för att alltför många ändringar ska ha gjorts utan ens kännedom.

Däremot var processen inte helt felfri. Bristande kunskaper inom git och versionshantering ledde till att vi stötte på en hel del problem i början av arbetet. Med hjälp av vår lärare samt google fick vi till slut kläm på det, men detta bromsade dock ner arbetet en del.


## IE8 Screenshot
Sidan fungerar även på IE8.<br>
![Bake IT IE8](./other/bakeitIE8.png)


### Krav
- [x] Mobile First
- [x] Responsive
- [x] SASS
- [x] Semantisk html
- [x] Flexbox
- [x] Meny
- [x] Mobil Webbläsare
- [x] Relativa måttenheter
- [x] Korrekt indentering
- [x] IE8
- [x] GitHub Pages
- [x] Tillgänglighetsanpassad
