---
title: EmbeddingLevel
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta i diritti di licenza per l'incorporamento del font.
type: docs
weight: 5786
url: /it/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum

Rappresenta i diritti di licenza per l'incorporamento del font.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Values

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) con questa impostazione indicano che possono essere incorporati e installati permanentemente sul sistema remoto da un'applicazione. L'utente del sistema remoto acquisisce gli stessi diritti, obblighi e licenze per quel font come l'acquirente originale del font, ed è soggetto allo stesso accordo di licenza per l'utente finale, diritto d'autore, brevetto di design e/o marchio come l'acquirente originale. |
| Restricted | 2 | [Fonts](../fonts/) che hanno solo questo bit impostato non devono essere modificati, incorporati o scambiati in alcun modo senza prima ottenere il permesso del proprietario legale. |
| PreviewPrint | 4 | Quando questo bit è impostato, il font può essere incorporato e temporaneamente caricato sul sistema remoto. I documenti contenenti font Preview & Print devono essere aperti \"read-only;\" non è possibile modificare il documento. |
| Editable | 8 | Quando questo bit è impostato, il font può essere incorporato ma deve essere installato temporaneamente solo su altri sistemi. In contrasto con i font Preview & Print, i documenti contenenti font Editable possono essere aperti in lettura, la modifica è consentita e le modifiche possono essere salvate. |
| NoSubsetting | 256 | Quando questo bit è impostato, il font non può essere sottocampionato prima dell'incorporamento. Altre restrizioni di incorporamento specificate nei bit 0-3 e 9 si applicano comunque. |
| BitmapOnly | 512 | Quando questo bit è impostato, solo le bitmap contenute nel font possono essere incorporate. Nessun dato di contorno può essere incorporato. Se non ci sono bitmap disponibili nel font, allora il font è considerato non incorporabile e i servizi di incorporamento falliranno. |

## Vedi anche

* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)