# Unverantwortli.ch

Die Liste der Responsible Disclosure-Gegner

## Format

Die Liste besteht aus `fools`, einer Liste, deren Einträge wiederum aus folgenden Einträge besteht:
- `name`: Name des Unternehmens (String)
- `year`: Jahr des Vorfalles (String)
- `country`: Land des Vorfalles/Unternehmens (ISO 3166-2, String)
- `proofs`: Quellen (String-Liste)

### Beispiel

```
  - name: CDU
    year: 2021
    year: DE
    proofs:
      - https://www.ccc.de/de/updates/2021/ccc-meldet-keine-sicherheitslucken-mehr-an-cdu
```
