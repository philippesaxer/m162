# m162

# Lernjournal Tag 1

- [GitHub Einführung](#github-einführung)
- [Markdown Tutorial](#markdown-tutorial)

## Github Einführung:
* Neues Repositorie erstellen und bennen
* Readme.md auf on stellen
* Lehrer hinzüfugen indem man den Repository Link in Teams einfügt bie **Repo Links**
* File erstellen und bennen
* Text/Code schreiben

## [Markdown Tutorial](https://www.markdowntutorial.com/de/conclusion/)

# Lernjournal Tag 2

## Datenstruktur Überblick

- [Datenstruktur](#datenstruktur)
- [Arten von Daten](#arten-von-daten)
- [Verarbeitung unstrukturierter Daten](#verarbeitung-unstrukturierter-daten)
- [Strukturierungsgrad](#strukturierungsgrad)
  
### Datenstruktur
- Objekt zur **Speicherung und Organisation von Daten**.
- Charakterisiert durch **Daten + Operationen** (Zugriff, Verwaltung).
- Viele Spezialisierungen (z. B. **B-Bäume** für Datenbanken).
- Wahl der Datenstruktur beeinflusst **Laufzeit & Speicherbedarf**.

### Arten von Daten
- **Strukturiert**: klares Schema (Tabellen, Bäume, Datenbanken).
- **Unstrukturiert**: keine feste Struktur (Texte, Audio).
- **Semi-strukturiert**: teils geordnet (z. B. E-Mail: Metadaten klar, Inhalt frei).

### Verarbeitung unstrukturierter Daten
- Erfordert **Modellierung** oder Verfahren wie:
  - **Textmining** (statistisch, NLP, maschinelles Lernen).
  - **Linguistische Methoden** (reduzieren Mehrdeutigkeit, schneller, aber menschliche Kontrolle nötig).

### Strukturierungsgrad
- **Schwach**: unsortiert, leicht einzufügen, schwer auszuwerten.  
- **Mäßig**: Tabellen/Listen, gute Auswertungen.  
- **Stark**: Datenbanken, sehr auswertbar, Einfügen aufwändig.  

> **Kernidee:** Je stärker Daten strukturiert sind, desto besser lassen sie sich **suchen und analysieren**, aber desto höher der **Aufwand bei der Pflege**.
# Statistik – Datentypen, Skalen & Häufbarkeit

Kurzüberblick über **diskrete vs. stetige Daten**, **Skalentypen** (Nominal, Ordinal, Kardinal) und **Häufbarkeit** mit Beispielen aus TBZ (Abteilung IT).

---

## Inhalt
- [Diskrete vs. Stetige Daten](#diskrete-vs-stetige-daten)
- [Skalentypen](#skalentypen)

---

## Diskrete vs. Stetige Daten

| Typ       | Definition                                                                 | Beispiel (TBZ)                                                                 |
|-----------|-----------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| **Diskret**  | Werte **abzählbar** (endliche/abzählbar unendliche Anzahl von Ausprägungen) | Sie werden in einem Fragebogen an der TBZ (Abteilung IT) gefragt, welches ihr Lieblingsmodul ist. Es gibt nur eine spezifische Anzahl im Berufsbild Informatik. Die möglichen Werte sind abzählbar.           |
| **Stetig**   | Werte **nicht abzählbar** (kontinuierliche Skala)                         | Sie werden in einem Fragebogen an der TBZ (Abteilung IT) gefragt, ob sie Kommentare zu dem Modul m162 haben. Die möglichen Antworten sind nicht abzählbar, da jede Person beliebigen Text schreiben kann.

---

## Skalentypen

### Nominalskala
- **Keine Rangordnung** zwischen den Ausprägungen.
- **Beispiel**: Lieblingsmodul – alle Module sind gleichwertig.

### Ordinalskala
- **Rangordnung vorhanden**, **Abstände nicht** gleich interpretierbar.
- **Beispiel**: Schulnoten für **m162** – Note 5 > Note 4, aber der „Abstand“ 4→5 ist nicht zwingend so groß wie 5→6.

### Kardinalskala
- **Rangordnung** **und** **gleichmäßige, interpretierbare Abstände**.
- **Beispiel**: Trinkmenge pro Tag (z. B. Liter/Deziliter) – 2 L > 1 L und der Abstand 1→2 L entspricht 2→3 L.
- **Hinweis**: Noten sind **nicht kardinal**, da die „Abstände“ zwischen Noten nicht gleich groß sein müssen.

```mermaid
flowchart TD
    A[Merkmals- & Skalentypen] --> B[Nominal]
    A --> C[Ordinal]
    A --> D[Kardinal]
    B:::nominal --> B1(Beispiele: Lieblingsmodul)
    C:::ordinal --> C1(Beispiele: Noten)
    D:::kardinal --> D1(Beispiele: Liter/Tag)
    classDef nominal fill:#e8f0fe,stroke:#4663ff,stroke-width:1px,color:#1a2b6b;
    classDef ordinal fill:#fff7e6,stroke:#ff9f0a,stroke-width:1px,color:#7a3e00;
    classDef kardinal fill:#e8fff0,stroke:#22a06b,stroke-width:1px,color:#0b4b33;
