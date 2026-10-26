---
title: LinkEmbedDecision
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt hoe het object wordt verwerkt tijdens het opslaan.
type: docs
weight: 911
url: /nl/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enum

Bepaalt hoe het object wordt verwerkt tijdens het opslaan.

```cpp
enum class LinkEmbedDecision
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Link | 0 | Object wordt extern opgeslagen, verwezen via URL |
| Embed | 1 | Object moet worden ingesloten in een gegenereerd bestand indien mogelijk. Als insluiten onmogelijk is, wordt GetUrl aangeroepen en, afhankelijk van het resultaat, wordt het object verwezen via URL of genegeerd. |
| Ignore | 2 | Object wordt genegeerd. |

## Zie Ook

* Namespace [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)