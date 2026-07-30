---
title: WarningType
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un tipo di avviso.
type: docs
weight: 92
url: /it/aspose.slides.warnings/warningtype/
---
## WarningType enum

Rappresenta un tipo di avviso.

```cpp
enum class WarningType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| SourceFileCorruption | 0 | È stato rilevato un problema nel documento sorgente che rende molto probabile che il documento non possa essere aperto se salvato nel suo formato originale. |
| DataLoss | 1 | Testo, grafico, immagine o altri dati saranno completamente mancanti sia dall’albero del documento dopo il caricamento, sia dal documento creato dopo il salvataggio. |
| MajorFormattingLoss | 2 | Perdita di formattazione maggiore. |
| MinorFormattingLoss | 3 | Perdita di formattazione minore. |
| CompatibilityIssue | 4 | Questo è un problema noto che impedirà l’apertura del documento da parte di alcuni agenti utente o versioni precedenti di agenti utente. |
| UnexpectedContent | 99 | Alcuni contenuti nel documento sorgente non sono stati riconosciuti (cioè non sono supportati); ciò potrebbe o meno causare problemi o comportare una perdita di dati/formattazione. |

## Vedi anche

* Spazio dei nomi [Aspose::Slides::Warnings](../)
* Libreria [Aspose.Slides](../../)