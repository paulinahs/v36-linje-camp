## Flex vs Grid

På min linje-sida använder jag `grid` i `.tabla` för att visa avgångarna. Jag valde `grid-template-columns: 1fr 1fr 1fr` eftersom innehållet behöver visas i både rader och kolumner, ungefär som en avgångstavla.

Destinationskorten ligger i `.kort-rad` där jag använder `flex`. Med `gap` och `flex-wrap` placeras korten bredvid varandra och flyttas ner till nästa rad om det inte finns plats. Här passar `flex` bättre eftersom det handlar om en rad med liknande kort och inte ett rutnät.

## Ägarskap

Jag förstår koden jag har skrivit och kan förklara hur den fungerar. AI har hjälpt mig med idéer och förklaringar, men jag har själv gjort arbetet och kan felsöka och ändra koden vid behov.