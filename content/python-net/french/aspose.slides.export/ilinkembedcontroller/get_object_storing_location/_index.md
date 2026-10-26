---
title: get_object_storing_location method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Détermine où l'objet doit être stocké.
Cette méthode est appelée une fois pour chaque id d'objet.
Il n'est pas garanti qu'il n'y aura pas deux objets avec les mêmes données, semanticName et contentType mais avec des id différents.

### Renvoie

Décision



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| id | **int** | Object id. This id is saving operation-wide unique. |
| entity_data | **bytes** | Object binary data. This parameter can be None, if object binary data is not generated yet. |
| semantic_name | **str** | Some short text, describing meaning of object. Controller may use this as a part of external object name, but it is up to dispatcher to ensure that names will be unique and contain only allowed characters. |
| content_type | **str** | MIME type of object. |
| recomended_extension | **str** | File name extension, recommended for this MIME type. |



### Voir aussi
* classe [`ILinkEmbedController`](/slides/python-net/fr/aspose.slides.export/ilinkembedcontroller)
* énumération [`LinkEmbedDecision`](/slides/python-net/fr/aspose.slides.export/linkembeddecision)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)