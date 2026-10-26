---
title: LinkEmbedDecision
second_title: Referência da API Aspose.Slides para C++
description: Determina como o objeto será processado durante a gravação.
type: docs
weight: 911
url: /pt/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enum

Determina como o objeto será processado durante a gravação.

```cpp
enum class LinkEmbedDecision
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Link | 0 | O objeto será armazenado externamente, referenciado por URL |
| Embed | 1 | O objeto deve ser incorporado a um arquivo gerado, se possível. Se a incorporação for impossível, GetUrl será chamado e, dependendo do resultado, o objeto será referenciado por URL ou ignorado. |
| Ignore | 2 | O objeto será ignorado. |

## Veja Também

* Namespace [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)