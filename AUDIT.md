# Min granskning av fullstackprojektet

**Datum:** 2026-11-11  
**Projekt:** Fullstack Starter (.NET 10, React och SQLite)

## Så gjorde jag

Jag skapade ett eget GitHub-repo från lärarens startprojekt och klonade det till Visual Studio.

Först hade jag problem med .NET-versionen, men efter att ha installerat och använt .NET 10 kunde jag starta projektet.

Jag testade att lägga till en uppgift och kontrollerade att den fanns kvar efter att sidan uppdaterades. Jag körde också automatiska tester och kontrollerade kodens formatering.

## Min checklista

0 = saknas, 1 = kan förbättras, 2 = fungerar bra.

| Kontroll | Poäng | Min kommentar |
|---|---|---|
| Controllers och services | 2 | Koden är tydligt uppdelad. |
| DTOs | 2 | Projektet använder DTOs. |
| Frontendstruktur | 2 | React är uppdelat i mappar och komponenter. |
| Tester | 2 | Alla 9 tester blev godkända. |
| Validering | 2 | Backend kontrollerar tomma och för långa titlar. |
| Felmeddelanden | 1 | Felhanteringen vid sparande kan förbättras. |
| Laddning och tom lista | 2 | React visar laddning och meddelande för tom lista. |
| README | 1 | Instruktionerna fungerade men kan förtydligas. |
| .gitignore | 2 | bin, obj och node_modules är undantagna. |
| Lösenord och nycklar | 1 | Inga synliga hemligheter i appsettings.json, men hela historiken är inte säkerhetsgranskad. |
| Commit-historik | 1 | Repot har bara en första commit, så historiken är svår att bedöma. |
| Formatering | 2 | Både .NET och Prettier klarade kontrollerna. |

**Totalt: 20 av 24 poäng.**

## Mina fem viktigaste förbättringar

1. Förbättra felmeddelanden när en uppgift inte kan sparas.
2. Förtydliga README och instruktionerna för .NET 10.
3. Kontrollera och utveckla GitHub Actions så att tester körs vid Pull Requests.
4. Lägga till fler frontendtester för felhantering.
5. Förbättra säkerhetskontrollen för lösenord och nycklar.

## Min reflektion

Jag tycker att projektet har en bra grund och fungerade bra när jag väl fick igång det. Jag lärde mig att det är viktigt med tydliga instruktioner och automatiska tester.

Jag hittade också saker som kan förbättras, framför allt felhantering, dokumentation och säkerhetskontroller.
