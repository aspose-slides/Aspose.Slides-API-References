---
title: only_load_document_properties property
second_title: Aspose.Slides للغة بايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties خاصية
هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور.
القيمة true تعني أنه يجب تحميل خصائص المستند فقط من ملف عرض مشفر ويجب تجاهل كلمة المرور.
القيمة false تعني أنه يجب تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة.
إذا لم يكن العرض مشفرًا فإن قيمة الخاصية تُهمل دائمًا.
إذا لم تكن خصائص المستند لملف مشفر عامة وكانت قيمة الخاصية true فإن خصائص المستند لا يمكن تحميلها وسيتم إلقاء استثناء.
قابلة للقراءة والكتابة **bool**.

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
* فئة [`ILoadOptions`](/slides/python-net/ar/aspose.slides/iloadoptions)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)