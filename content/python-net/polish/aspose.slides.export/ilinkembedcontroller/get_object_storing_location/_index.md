---
title: get_object_storing_location method
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Określa, gdzie obiekt powinien być przechowywany.
            Ta metoda jest wywoływana raz dla każdego id obiektu.
            Nie ma gwarancji, że nie będzie dwóch obiektów z tymi samymi danymi, semanticName i contentType, ale o różnych id.

### Zwraca

Decyzja

```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| id | **int** | Identyfikator obiektu. To id jest unikalne w całej operacji zapisu. |
| entity_data | **bytes** | Dane binarne obiektu. Ten parametr może być None, jeśli dane binarne obiektu nie zostały jeszcze wygenerowane. |
| semantic_name | **str** | Krótki tekst opisujący znaczenie obiektu. Kontroler może używać tego jako części zewnętrznej nazwy obiektu, ale to od dyspozytora zależy zapewnienie, że nazwy będą unikalne i zawierały wyłącznie dozwolone znaki. |
| content_type | **str** | Typ MIME obiektu. |
| recomended_extension | **str** | Rozszerzenie nazwy pliku, zalecane dla tego typu MIME. |



### Zobacz także
* klasa [`ILinkEmbedController`](/slides/python-net/pl/aspose.slides.export/ilinkembedcontroller)
* wyliczenie [`LinkEmbedDecision`](/slides/python-net/pl/aspose.slides.export/linkembeddecision)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)