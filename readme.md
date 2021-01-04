# Locatiedata

In deze repository zijn wat datasets met toponiemen opgenomen die  nuttig kunnen zijn.

## Atlas of Mutual Heritage

De [Atlas of Mutual Heritage](https://www.atlasofmutualheritage.nl/) bevat zo'n 1300 locaties (plaatsen, gebieden, forten, etc.) die van belang waren in de historie van zowel de WIC als de VOC. Bij die locaties zijn zo'n 4000 naamvarianten opgenomen die je in bronnen tegen zou kunnen komen.

In de bestanden hieronder is bij 730+ locaties een Wikidata identifier opgenomen. Wikidata wordt door steeds meer instellingen gebruikt als 'thesaurus', en zo is het weer wat eenvoudiger om verschillende databronnen te verbinden. Omgekeerd is bij honderden forten op Wikidata een link naar de Atlas of Mutual Heritage gelegd.

Het leggen van deze verbindingen is gebeurd binnen het project bij [Slimmer zoeken in archieven](https://nlaic.com/use-cases/aincient-en-partners-slimmer-doorzoeken-van-archieven-door-de-inzet-van-ai-en-crowdsourcing/).

- [atlasmutualheritage.geojson](atlasmutualheritage.geojson) bevat alle locaties die van coördinaten voorzien zijn. In de `properties` zijn zowel de naamvarianten als de link naar Wikidata (indien reeds gelegd) te vinden.
- [atlasmutualheritage.csv](atlasmutualheritage.csv) is een csvbestand met een regel voor elk voor elk van de 4000 naamvarianten - handig als je een in een bron gevonden naamvarianten wil thuisbrengen.