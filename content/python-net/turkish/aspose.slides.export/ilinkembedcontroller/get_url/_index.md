---
title: get_url method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Harici bir nesneye ait bir URL döndürür.
            Bu yöntem, **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.LINK`](/slides/python-net/tr/aspose.slides.export/linkembeddecision/LINK) döndürdüğünde her zaman çağrılır ve **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.EMBED`](/slides/python-net/tr/aspose.slides.export/linkembeddecision/EMBED) döndürdüğünde ancak gömme mümkün olmadığında çağrılabilir.
            Aynı nesne kimliği için birden çok kez çağrılabilir.

### Dönüş

Harici nesnenin URL'si veya bu nesne göz ardı edilmesi gerekiyorsa None.



```python
def get_url(self, id, referrer):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| id | **int** | Nesne kimliği. Bu kimlik işlemlere genel olarak benzersizdir. |
| referrer | **int** | Referans veren nesnenin kimliği veya kök belge tarafından referans alınıyorsa 0. Göreli link oluşturmak için kullanılabilir. |



### Ayrıca Bakınız
* sınıf [`ILinkEmbedController`](/slides/python-net/tr/aspose.slides.export/ilinkembedcontroller)
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)