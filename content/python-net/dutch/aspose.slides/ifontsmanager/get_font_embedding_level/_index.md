---
title: get_font_embedding_level method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ifontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Bepaalt het insluitingsniveau van een lettertype op basis van de gegeven byte-array en lettertype-naam.

### Retour

Het insluitingsniveau van het opgegeven lettertype.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_bytes | **bytes** | De byte-array met de lettertype-gegevens. |
| font_name | **str** | De naam van het lettertype. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wordt opgegooid wanneer `font_bytes` None is. |



### Zie ook
* enumeratie [`EmbeddingLevel`](/slides/python-net/nl/aspose.slides/embeddinglevel)
* klasse [`IFontsManager`](/slides/python-net/nl/aspose.slides/ifontsmanager)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)