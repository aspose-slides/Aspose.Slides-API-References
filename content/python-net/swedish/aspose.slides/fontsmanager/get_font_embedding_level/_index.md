---
title: get_font_embedding_level method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Bestämmer inbäddningsnivån för ett teckensnitt från den givna byte-arrayen och teckensnittets namn.

### Returnerar

Inbäddningsnivån för det angivna teckensnittet.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_bytes | **bytes** | Byte-arrayen som innehåller teckensnittets data. |
| font_name | **str** | Namnet på teckensnittet. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kastas när `font_bytes` är None. |



### Se även
* uppräkning [`EmbeddingLevel`](/slides/python-net/sv/aspose.slides/embeddinglevel)
* klass [`FontsManager`](/slides/python-net/sv/aspose.slides/fontsmanager)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)