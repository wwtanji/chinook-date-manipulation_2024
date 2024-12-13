
# Implementácia ETL procesu pre analýzu dát z databázy Chinook

Tento repozitár obsahuje implementáciu ETL procesu pre analýzu dát z databázy Chinook. Proces zahŕňa kroky na extrahovanie, transformovanie a načítanie dát do dimenzionálneho modelu v Snowflake. Tento model umožňuje vizualizáciu a analýzu údajov o hudobných albumoch, skladbách, zákazníkoch a predajoch.

## 1. Úvod a popis zdrojových dát

Cieľom tejto práce je vizualizácia a prezentácia dát prostredníctvom grafických zobrazení, ktoré umožňujú lepšie pochopenie a interpretáciu informácií.

### Zdrojové dáta:
- `album.csv`: Informácie o hudobných albumoch.
- `artist.csv`: Detaily o interpretoch.
- `customer.csv`: Informácie o zákazníkoch, vrátane ich kontaktných údajov.
- `employee.csv`: Dáta o zamestnancoch, ktorí spravujú objednávky.
- `genre.csv`: Žánre hudby.
- `invoice.csv`: Faktúry a informácie o predajoch.
- `invoiceline.csv`: Detaily o položkách na faktúrach.
- `mediatype.csv`: Typy médií, ako napríklad MP3 alebo AAC.
- `playlist.csv`: Zoznamy skladieb vytvorené používateľmi.
- `playlisttrack.csv`: Väzba medzi playlistami a skladbami.
- `track.csv`: Informácie o skladbách, vrátane názvov, žánrov a trvania.
