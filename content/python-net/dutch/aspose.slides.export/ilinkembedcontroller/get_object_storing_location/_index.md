---
title: get_object_storing_location method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Bepaalt waar het object moet worden opgeslagen.
            Deze methode wordt één keer aangeroepen voor elke object-id.
            Het is niet gegarandeerd dat er niet twee objecten met dezelfde data, semanticName en contentType bestaan, maar met verschillende id's.

### Retourwaarde

Beslissing



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```



| Parameter | Type | Beschrijving |
| :- | :- | :- |
| id | **int** | Object-id. Deze id is uniek voor de gehele bewaaroperatie. |
| entity_data | **bytes** | Object binaire gegevens. Deze parameter kan None zijn, als de binaire gegevens van het object nog niet zijn gegenereerd. |
| semantic_name | **str** | Korte tekst die de betekenis van het object beschrijft. De controller kan dit gebruiken als onderdeel van de externe objectnaam, maar het is aan de dispatcher om ervoor te zorgen dat namen uniek zijn en alleen toegestane tekens bevatten. |
| content_type | **str** | MIME-type van het object. |
| recomended_extension | **str** | Bestandsextensie, aanbevolen voor dit MIME-type. |



### Zie ook
* class [`ILinkEmbedController`](/slides/python-net/nl/aspose.slides.export/ilinkembedcontroller)
* enumeration [`LinkEmbedDecision`](/slides/python-net/nl/aspose.slides.export/linkembeddecision)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)