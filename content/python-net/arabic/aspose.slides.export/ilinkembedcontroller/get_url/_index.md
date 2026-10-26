---
title: get_url method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Returns an URL to an external object.
            يتم دائمًا استدعاء هذه الطريقة إذا **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** أرجع [`LinkEmbedDecision.LINK`](/slides/python-net/ar/aspose.slides.export/linkembeddecision/LINK) وقد تُستدعى إذا **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** أرجع [`LinkEmbedDecision.EMBED`](/slides/python-net/ar/aspose.slides.export/linkembeddecision/EMBED) لكن الدمج مستحيل.
            يمكن استدعاؤها عدة مرات لنفس معرف الكائن.

### الإرجاع

عنوان URL للكائن الخارجي أو None إذا كان ينبغي تجاهل هذا الكائن.



```python
def get_url(self, id, referrer):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| id | **int** | معرف الكائن. هذا المعرف فريد على مستوى العملية بأكملها. |
| referrer | **int** | معرف الكائن المرجع أو 0 إذا كان الكائن مُشارًا إليه من قبل المستند الجذر. قد يُستخدم لإنشاء رابط نسبي. |



### انظر أيضًا
* فئة [`ILinkEmbedController`](/slides/python-net/ar/aspose.slides.export/ilinkembedcontroller)
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)