---
title: set_embedded_data method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
يضبط معلومات حول بيانات OLE المضمنة.


```python
def set_embedded_data(self, embedded_data):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo) | البيانات المضمنة [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo) |

### ملاحظات

هذه الطريقة تغير خصائص الكائن لتعكس البيانات الجديدة وتضبط علم IsObjectLink إلى false، مما يدل على أن كائن OLE مضمّن.

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما يكون معامل embeddedData هو None. |



### انظر أيضًا
* الفئة [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo)
* الفئة [`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)