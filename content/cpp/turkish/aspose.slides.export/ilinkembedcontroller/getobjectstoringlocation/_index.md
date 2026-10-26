---
title: GetObjectStoringLocation()
second_title: Aspose.Slides for C++ API Referansı
description: Nesnenin nerede depolanması gerektiğini belirler. Bu yöntem, her nesne kimliği için bir kez çağrılır. Aynı veri, semanticName ve contentType'a sahip ancak farklı kimliğe sahip iki nesnenin olmayacağı garantilenmez.
type: docs
weight: 1
url: /tr/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) yöntemi


Nesnenin nerede depolanması gerektiğini belirler. Bu yöntem, her nesne id için bir kez çağrılır. Aynı veri, semanticName ve contentType'a sahip ancak farklı id'ye sahip iki nesnenin olmayacağı garanti edilmez.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | **int32_t** | Nesne id. Bu id kaydetme işlemi boyunca benzersizdir. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Nesne ikili verisi. Bu parametre, nesne ikili verisi henüz üretilmemişse null olabilir. |
| semanticName | [System::String](../../../system/string/) | Nesnenin anlamını açıklayan kısa bir metin. Controller bu metni dış nesne adının bir parçası olarak kullanabilir, ancak adların benzersiz olmasını ve yalnızca izin verilen karakterleri içermesini sağlamak dispatcher'a kalmıştır. |
| contentType | [System::String](../../../system/string/) | Nesnenin MIME türü. |
| recomendedExtension | [System::String](../../../system/string/) | Bu MIME türü için önerilen dosya adı uzantısı. |

### Dönüş Değeri

Decision

## See Also

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)