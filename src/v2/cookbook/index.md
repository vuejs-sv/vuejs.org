---
title: Introduktion
type: cookbook
order: 0
---

## Kokboken vs guiden

Hur skiljer sig kokboken från guiden? Varför behövs den?

* **Större fokus**: I guiden berättar vi en historia. Varje sektion bygger på och förutsätter kunskap från tidigare sektioner. I kokboken kan (och borde) varje recept stå för sig själv. Detta betyder att recept kan fokusera på en specifik aspekt i Vue i stället för att ge en allmän överblick.

* **Ytterligare fördjupning**: För att undvika att guiden blir för lång försöker vi göra varje exempel så simpelt och kompakt som möjligt för att hjälpa dig förstå varje funktion. Efter det går guiden vidare. I kokboken kan vi inkludera komplicerade exempel och kombinera dem med funktioner av olika slag. Varje recept kan vara hur långt och detaljerat det än behövs för att utforska sin nisch.

* **Lär JavaScript**: I guiden förväntas åtminstone medelmåttig ES5 JavaScript kunskap. Vi förklarar t.ex. inte hur `Array.prototype.filter` fungerar i en computed property (beräknad egenskap) som filtrerar en lista. I kokboken kan dock grundläggande JavaScript-funktioner (ES6/2015+ inkluderat) utforskas och förklaras i kontexten av hur det hjälper oss att bygga bättre Vue-applikationer.

* **Utforska ekosystemet**: För avancerade funktioner förväntas kunskap om ekosystemet. T.ex. om du vill använda enkla komponentfiler i Webpack så förklarar vi inte hur du konfigurerar inställningar som inte är Vue-relaterade i Webpack. I kokboken har vi större utrymme för att utforska dessa ekosystembibliotek i djupet - åtminstone till den grad som är övervägande användbart för Vue-utvecklare.

<p class="tip">Vänligen notera att även med alla dessa skillnader så är kokboken inte en steg-för-steg manual. Största delen av innehållet förväntar att du ha baskunskap i koncept så som HTML, CSS, JavaScript, npm/yarn, etc.</p>

## Bidra till kokboken

### Vad vi letar efter

Kokboken ger utvecklare exempel som kan jobbas vidare på och som behandlar både vanliga och intressanta användningsområden, men även progressivt förklarar komplexa detaljer. Vårt mål är att förbigå ett simpelt introduktionsexempel och demonstrera koncept som har bredare användningsområden, men även varningar att se upp för.

Om du är intresserad av att bidra, starta vänligen med att skapa en issue under taggen **cookbook idea** med ditt koncept så att vi kan hjälpa till med att utföra en vällyckad pull request. Efter att din idé har blivit godkänd, vänligen följ mallen nedan så noggrant som möjligt. Några sektioner är obligatoriska och några är valfria. Det rekommenderas starkt att följa den numeriska ordningen, med det krävs inte.

Recept borde:

> * Lösa ett specifikt, vanligt problem
> * Starta med det enklaste möjliga exemplet
> * Introducera komplexitet en gång i taget
> * Länka till andra dokument i stället för att förklara på nytt
> * Beskriva problemet, kunskap antas inte
> * Förklara processen, ge inte endast slutresultatet
> * Förklara för- och nackdelar med din strategi men även när den är (o)lämplig
> * Nämna alternativa lösningar (om relevanta), men lämna fördjupad utforskning till ett separat recept

Vi ber att du följer mallen nedan. Vi förstår dock att det kan uppstå tillfällen när du kan vara tvungen att avvika för att förtydliga eller för att få texten att flöda. Hursomhelst borde alla recept vid något tillfälle diskutera nyanser med gjorda val genom att följa dessa mallar, helst genom exemplet på alternativa mönster.

### Grundexempel

_obligatorisk_

1.  Artikulera problemet i en mening eller två.
2.  Förklara den enklaste möjliga lösningen i en mening eller två.
3.  Visa en liten kodsnutt.
4.  Förklara vad detta åstadkommer i en mening.

### Detaljer om receptvärdet

_obligatorisk_

1.  Behandla vanliga frågor som man kan ha när man tittar på exemplet. (Blockquotes är bra för detta)
2.  Visa exempel på vanliga misstag och hur de kan undvikas.
3.  Visa mycket enkla kodsnuttar av bra och dåliga mönster.
4.  Diskutera varför detta kan vara ett övertygande mönster. Länkar för referens krävs inte, men uppmuntras.

### Exempel i praxis

_obligatorisk_

Demonstrera koden som driver ett gemensamt eller intressant användningsområde, antingen genom:

1.  Att gå igenom några koncisa startexempel, eller
2.  Bifoga ett codepen/jsfiddle exempel

Om du väljer det senare alternativet borde du fortfarande förklara vad det är och vad det gör.

### Ytterligare kontext

_valfri_

Det är oerhört användbart att skriva lite om detta mönstret, var det kan tillämpas, varför det fungerar bra och gå igenom lite kod eller ge folk ytterligare litteratur.

### När detta mönster bör undvikas

_valfri_

Denna sektion krävs inte, men rekommenderas starkt. Det är inte nödvändigt att skriva detta för något väldigt enkelt, t.ex. växlande klasser baserat på tillståndsförändringar, men för mer avancerade mönster såsom mixins är det viktigt. Svaret på de flesta utvecklingsfrågor är ["Det beror på!"](https://codepen.io/rachsmith/pen/YweZbG), denna sektion omfattar det. Här tar vi en ärlig titt på när mönstret är användbart och när det bör undvikas, eller när något fullständigt annat bör övervägas.

### Alternativa mönster

_obligatorisk_

Denna sektion krävs ifall du skrivit sektionen ovan om undvikande. Det är viktigt att utforska andra metoder så att folk som blivit tilsagda att något bör undvikas i vissa situationer inte lämnas förundrande. Tänk dig att webben är ett stort tält och att många människor har olika kodbasstrukturer som löser olika mål. Är appen stor eller liten? Integrerar de Vue i ett befintligt projekt, eller byggs det från grunden? Försöker deras användare endast nå ett eller flera mål? Finns det mycket asynkron data? Alla dessa problem påverkar alternativa implementeringar. Ett bra kokbokrecept ger utvecklare det här sammanhanget.

## Tack

Det är tidskrävande att bidra till dokumentation, så om du spenderat tiden med att sända en PR till denna sektion av dokumentationen gör du det med våran tacksamhet.
