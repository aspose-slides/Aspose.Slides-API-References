---
title: LinkEmbedDecision
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, jak bude objekt během ukládání zpracován.
type: docs
weight: 911
url: /cs/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enum

Určuje, jak bude objekt během ukládání zpracován.

```cpp
enum class LinkEmbedDecision
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Link | 0 | Objekt bude uložen externě, odkazován pomocí URL |
| Embed | 1 | Objekt by měl být vložen do generovaného souboru, pokud je to možné. Pokud vkládání není možné, bude zavolána metoda GetUrl a v závislosti na výsledku bude objekt odkazován pomocí URL nebo bude ignorován. |
| Ignore | 2 | Objekt bude ignorován. |

## Viz také

* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)