---
title: ILinkEmbedController class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController فئة

واجهة رد نداء تُستخدم لتحديد كيفية معالجة الكائن أثناء الحفظ.

نوع ILinkEmbedController يعرض الأعضاء التالية:

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/ar/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | يحدد أين يجب تخزين الكائن.<br/>            تُستدعى هذه الطريقة مرة واحدة لكل معرف كائن.<br/>            لا يُضمن عدم وجود كائنين بنفس البيانات وsemanticName وcontentType لكن بمعرف مختلف. |
| [`get_url(self, id, referrer)`](/slides/python-net/ar/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | إرجاع عنوان URL لكائن خارجي.<br/>            تُستدعى هذه الطريقة دائمًا إذا **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** أرجعت [`LinkEmbedDecision.LINK`](/slides/python-net/ar/aspose.slides.export/linkembeddecision/LINK) وقد تُستدعى إذا **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** أرجعت [`LinkEmbedDecision.EMBED`](/slides/python-net/ar/aspose.slides.export/linkembeddecision/EMBED) لكن التكامل غير ممكن.<br/>            يمكن استدعاؤها عدة مرات لنفس معرف الكائن. |
| [`save_external(self, id, entity_data)`](/slides/python-net/ar/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | يحفظ الكائن الخارجي. |


### انظر أيضًا
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)