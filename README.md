# European-Broadband-Markets-ETL
Implementácia ELT procesu v Snowflake a vytvorenie dátového skladu so schémou Star na datasete [European-Broadband-Markets-2017](https://app.snowflake.com/marketplace/listing/GZSVZ6EW2A/expert-intelligence-european-broadband-markets-2017?search=europe&pricing=free&available=available). Zameraním projektu je preskúmať pokrytie jednotlivých technológií prenosu dát na území Európy v roku 2017.

<hr>

## 1. Úvod a popis zdrojových dát
Analyzujeme dáta o technológiach prenosu dát, ich pokrytí v jednotlivých štátoch a ich regiónov. Cieľ je:
- Zistiť prístupnosť prenosových technológií
- Identifikovať regióny

Dataset obsahuje jednu tabulku `EUROPEAN_BROADBAND_MARKETS_2017_FREE_DATASET`, ktorá obsahuje údáje o počte obyvateľov, domácností podľa regiónov a štátov a štatistiky o využívaní jednotlivých technológií (DSL, VDSL, FTTP...). 

Účelom ELT procesu je tieto dáta pripraviť, transformovať a sprístupniť na viacdimenzionálnu analýzu.

<hr>

### 1.1 ERD diagram zdrojového datasetu
Relačný model dát z tohoto datasetu je znázornený v entitno-relačnom diagrame:
<p align="center">
  <img src="https://github.com/snickers-c/European-Broadband-Markets-ETL/blob/main/img/Obr%C3%A1zok%201%20-%20Entitno_rela%C4%8Dn%C3%A1%20sch%C3%A9ma.png">
  <br>
  <em>Obrázok 1 - Entitno_relačná schéma</em>
</p>

<hr>

## 2. Dimenzionálny model

<hr>

## 3. ELT proces v Snowflake

<hr>

## 4. Vizualizácia dát

<hr>

**Autori:** [Matúš Gabaš](https://github.com/snickers-c) a [Juraj Daniš](https://github.com/Jur1n0)
