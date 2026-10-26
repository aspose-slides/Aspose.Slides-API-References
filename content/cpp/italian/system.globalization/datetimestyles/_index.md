---
title: DateTimeStyles
second_title: Riferimento API Aspose.Slides per C++
description: Definisce le opzioni di formattazione di data e ora. Flag a bit.
type: docs
weight: 456
url: /it/system.globalization/datetimestyles/
---
## DateTimeStyles enum

Definisce le opzioni di formattazione di data e ora. Flag a bit.

```cpp
enum class DateTimeStyles : int32_t
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Predefinito. |
| AllowLeadingWhite | 1 | Ignora gli spazi bianchi iniziali. |
| AllowTrailingWhite | 2 | Ignora gli spazi bianchi finali. |
| AllowInnerWhite | 4 | Ignora gli spazi bianchi interni. |
| AllowWhiteSpaces | n/a | Ignora tutti gli spazi bianchi. |
| NoCurrentDateDefault | 8 | Durante l'analisi di una stringa data/ora, se anno/mese/giorno sono tutti mancanti, imposta la data predefinita a 0001/1/1, invece dell'anno/mese/giorno corrente. |
| AdjustToUniversal | 16 | Durante l'analisi di una stringa data/ora, se è presente uno specificatore di fuso orario ("GMT","Z","+xxxx","-xxxx"), regoleremo l'ora analizzata in base a GMT. |
| AssumeLocal | 32 | Se non è specificato alcun fuso orario, utilizza il fuso orario locale. |
| AssumeUniversal | 64 | Se non è specificato alcun fuso orario, utilizza UTC. |
| RoundtripKind | 128 | Cerca di preservare se l'input è non specificato, locale o UTC. |

## Vedi anche

* Spazio dei nomi [System::Globalization](../)
* Libreria [Aspose.Slides](../../)