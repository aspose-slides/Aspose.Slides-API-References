---
title: only_load_document_properties property
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## خاصية only_load_document_properties
تكون هذه الخاصية منطقية إذا كان ملف العرض محميًا بكلمة مرور.
            القيمة true تعني أن خصائص المستند فقط يجب تحميلها من ملف عرض مشفر ويجب تجاهل كلمة المرور.
            القيمة false تعني أنه يجب تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة.
            إذا لم يكن العرض مشفرًا فسيتم دائمًا تجاهل قيمة الخاصية.
            إذا لم تكن خصائص المستند لملف مشفر عامة وكان قيمة الخاصية true، فإن خصائص المستند لا يمكن تحميلها وستُطرح استثناء.
            قابل للقراءة والكتابة **bool**.

### التعريف:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```

### انظر أيضًا
* الفئة [`LoadOptions`](/slides/python-net/ar/aspose.slides/loadoptions)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)