---
title: get_font_embedding_level method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ifontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Bestämmer inbäddningsnivån för ett teckensnitt från den angivna byte-arrayen och teckensnittets namn.

### Returnerar

Inbäddningsnivån för det angivna teckensnittet.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_bytes | **bytes** | Byte-arrayen som innehåller teckensnittsdatan. |
| font_name | **str** | Namnet på teckensnittet. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kastas när `font_bytes` är None. |



### Se också
* enumeration [`EmbeddingLevel`](/slides/python-net/sv/aspose.slides/embeddinglevel)
* class [`IFontsManager`](/slides/python-net/sv/aspose.slides/ifontsmanager)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)