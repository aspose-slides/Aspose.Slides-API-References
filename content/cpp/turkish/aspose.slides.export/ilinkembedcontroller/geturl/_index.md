---
title: GetUrl()
second_title: Aspose.Slides for C++ API Referansı
description: "Harici bir nesne için bir URL döndürür. Bu yöntem ILinkEmbedController::GetObjectStoringLocation LinkEmbedDecision::Link döndürdüğünde her zaman çağrılır ve ILinkEmbedController::GetObjectStoringLocation LinkEmbedDecision::Embed döndürdüğünde ancak gömme mümkün olmadığında çağrılabilir. Aynı nesne kimliği için birden fazla kez çağrılabilir."
type: docs
weight: 14
url: /tr/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) metodu


Harici bir nesne için bir URL döndürür. Bu yöntem [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) [LinkEmbedDecision::Link](../../linkembeddecision/) döndürdüğünde her zaman çağrılır ve [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) [LinkEmbedDecision::Embed](../../linkembeddecision/) döndürdüğünde ancak gömme mümkün olmadığında çağrılabilir. Aynı nesne kimliği için birden fazla kez çağrılabilir.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | **int32_t** | Nesne kimliği. Bu kimlik işlem boyunca benzersiz şekilde saklanır. |
| referrer | **int32_t** | Referans veren nesnenin kimliği veya kök belge tarafından referans edilen nesne ise 0. Göreceli bağlantı oluşturmak için kullanılabilir. |

### Dönüş Değeri

Harici nesnenin URL’si veya bu nesne yoksayılmalı ise null.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [ILinkEmbedController](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)