---
title: get_font_embedding_level method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Bepaalt het insluitingsniveau van een lettertype op basis van de opgegeven byte-array en lettertype-naam.

### Retour
Het insluitingsniveau van het opgegeven lettertype.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_bytes | **bytes** | De byte-array die de lettertype-gegevens bevat. |
| font_name | **str** | De naam van het lettertype. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wordt gegooid wanneer `font_bytes` None is. |



### Zie ook
* enumeration [`EmbeddingLevel`](/slides/python-net/nl/aspose.slides/embeddinglevel)
* class [`FontsManager`](/slides/python-net/nl/aspose.slides/fontsmanager)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)