---
title: get_object_storing_location method
second_title: Aspose.Slides pro Python – reference k .NET API
description: 
type: docs
url: /cs/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Určuje, kde by měl být objekt uložen.
            Tato metoda je volána jednou pro každé ID objektu.
            Není zaručeno, že nebudou dva objekty se stejnými daty, semanticName a contentType, ale s různým id.

### Návratová hodnota

Decision



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| id | **int** | ID objektu. Toto ID je během celé operace jedinečné. |
| entity_data | **bytes** | Binární data objektu. Tento parametr může být None, pokud binární data objektu ještě nebyla vygenerována. |
| semantic_name | **str** | Krátký text popisující význam objektu. Ovladač může použít toto jako součást externího názvu objektu, ale na dispečeru záleží, aby zajistil, že názvy budou jedinečné a budou obsahovat pouze povolené znaky. |
| content_type | **str** | MIME typ objektu. |
| recomended_extension | **str** | Přípona souboru doporučená pro tento MIME typ. |



### Viz také
* třída [`ILinkEmbedController`](/slides/python-net/cs/aspose.slides.export/ilinkembedcontroller)
* enumerace [`LinkEmbedDecision`](/slides/python-net/cs/aspose.slides.export/linkembeddecision)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)