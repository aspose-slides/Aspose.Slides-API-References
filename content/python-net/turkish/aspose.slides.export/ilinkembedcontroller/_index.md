---
title: ILinkEmbedController class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController sınıfı

Kaydetme sırasında nesnenin nasıl işleneceğini belirlemek için kullanılan geri çağırma arayüzü.

ILinkEmbedController türü aşağıdaki üyeleri sunar:

## Yöntemler

| Method | Description |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/tr/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Nesnenin nerede saklanması gerektiğini belirler.<br/>            Bu yöntem her nesne kimliği için bir kez çağrılır.<br/>            Aynı veri, semanticName ve contentType'a sahip ancak farklı kimliğe sahip iki nesnenin olmayacağı garanti edilmez. |
| [`get_url(self, id, referrer)`](/slides/python-net/tr/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Harici bir nesne için bir URL döndürür.<br/>            Bu yöntem **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.LINK`](/slides/python-net/tr/aspose.slides.export/linkembeddecision/LINK) döndürdüğünde her zaman çağrılır ve **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.EMBED`](/slides/python-net/tr/aspose.slides.export/linkembeddecision/EMBED) döndürdüğünde çağrılabilir ancak gömmek mümkün değildir.<br/>            Aynı nesne kimliği için birden fazla kez çağrılabilir. |
| [`save_external(self, id, entity_data)`](/slides/python-net/tr/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Harici nesneyi kaydeder. |


### Ayrıca Bakınız
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)