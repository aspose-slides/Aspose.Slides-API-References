---
title: HandleRepeatedSpaces
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica come gestire i caratteri di spazio regolare ripetuti durante l'esportazione Markdown.
type: docs
weight: 937
url: /it/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

Specifica come gestire i caratteri di spazio regolare ripetuti durante l'esportazione Markdown.

```cpp
enum class HandleRepeatedSpaces
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Tutti gli spazi sono conservati come caratteri di spazio regolare senza alcuna modifica. Non viene applicata alcuna trasformazione e gli spazi consecutivi multipli vengono esportati così come sono. |
| AlternateSpacesToNbsp | 1 | Converte le sequenze di due o più spazi regolari consecutivi alternando tra caratteri di spazio regolare e entità di spazio non interrottabile (**&nbsp;**). Il primo spazio è sempre mantenuto come spazio regolare. |
| MultipleSpacesToNbsp | 2 | Converte le sequenze di due o più spazi regolari consecutivi conservando il primo spazio come carattere di spazio regolare e sostituendo tutti gli spazi successivi con entità di spazio non interrottabile (**&nbsp;**). |

## Vedi anche

* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)