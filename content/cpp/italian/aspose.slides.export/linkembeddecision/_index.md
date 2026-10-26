---
title: LinkEmbedDecision
second_title: Riferimento API di Aspose.Slides per C++
description: Determina come l'oggetto verrà elaborato durante il salvataggio.
type: docs
weight: 911
url: /it/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enum

Determina come l'oggetto verrà elaborato durante il salvataggio.

```cpp
enum class LinkEmbedDecision
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Link | 0 | L'oggetto verrà memorizzato esternamente, referenziato tramite URL |
| Embed | 1 | L'oggetto dovrebbe essere incorporato in un file generato, se possibile. Se l'incorporamento è impossibile, verrà chiamato GetUrl e, a seconda del risultato, l'oggetto sarà referenziato tramite URL o ignorato. |
| Ignore | 2 | L'oggetto sarà ignorato. |

## Vedi anche

* Namespace [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)