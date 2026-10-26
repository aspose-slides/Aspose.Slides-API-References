---
title: get_object_storing_location method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Bestämmer var objektet ska lagras.
Denna metod anropas en gång för varje objekt-id.
Det är inte garanterat att det inte finns två objekt med samma data, semanticName och contentType men med olika id.

### Returns

Beslut



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| id | **int** | Objekt-id. Detta id är unikt för hela sparningsoperationen. |
| entity_data | **bytes** | Objektets binära data. Denna parameter kan vara None om den binära datan ännu inte har genererats. |
| semantic_name | **str** | Kort text som beskriver objektets betydelse. Kontrollen kan använda detta som en del av det externa objektets namn, men det är upp till dispatcher att säkerställa att namn är unika och bara innehåller tillåtna tecken. |
| content_type | **str** | MIME-typ för objektet. |
| recomended_extension | **str** | Filnamnstillägg som rekommenderas för denna MIME-typ. |



### Se även
* klass [`ILinkEmbedController`](/slides/python-net/sv/aspose.slides.export/ilinkembedcontroller)
* enumeration [`LinkEmbedDecision`](/slides/python-net/sv/aspose.slides.export/linkembeddecision)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)