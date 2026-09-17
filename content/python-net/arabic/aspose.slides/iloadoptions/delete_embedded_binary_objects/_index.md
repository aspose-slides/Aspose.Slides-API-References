---
title: delete_embedded_binary_objects property
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects خاصية
يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض التقديمي.

أنواع الكائنات الثنائية المدمجة:

* مشروع VBA [`IPresentation.vba_project`](/slides/python-net/ar/aspose.slides/ipresentation/vba_project)
* بيانات كائن OLE المدمج [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* بيانات ثنائية لـ ActiveX Control [`IControl.active_x_control_binary`](/slides/python-net/ar/aspose.slides/icontrol/active_x_control_binary)

قراءة/كتابة **bool**.

### ملاحظات

القيمة الافتراضية هي **false**.

### التعريف:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### انظر أيضًا
* فئة [`ILoadOptions`](/slides/python-net/ar/aspose.slides/iloadoptions)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)