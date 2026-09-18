---
title: get_object_storing_location method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Nesnenin nerede depolanması gerektiğini belirler.
Bu yöntem, her nesne kimliği için bir kez çağrılır.
Aynı veri, semanticName ve contentType'a sahip ancak farklı kimliğe sahip iki nesnenin olmayacağı garanti edilmez.

### Döndürür

Karar



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| id | **int** | Nesne kimliği. Bu kimlik, kaydetme işlemi boyunca benzersizdir. |
| entity_data | **bytes** | Nesne ikili verisi. Bu parametre, nesne ikili verisi henüz oluşturulmadıysa None olabilir. |
| semantic_name | **str** | Nesnenin anlamını tanımlayan kısa bir metin. Kontrolcü bunu harici nesne adının bir parçası olarak kullanabilir, ancak adların benzersiz olmasını ve yalnızca izin verilen karakterleri içermesini sağlamak göndericiye aittir. |
| content_type | **str** | Nesnenin MIME türü. |
| recomended_extension | **str** | Bu MIME türü için önerilen dosya adı uzantısı. |



### Bakınız
* sınıf [`ILinkEmbedController`](/slides/python-net/tr/aspose.slides.export/ilinkembedcontroller)
* enumeration [`LinkEmbedDecision`](/slides/python-net/tr/aspose.slides.export/linkembeddecision)
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)