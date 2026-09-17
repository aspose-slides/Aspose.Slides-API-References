---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded خاصية
هذه الخاصية منطقية إذا كان ملف العرض محمياً بكلمة مرور وخصائص المستند لهذا الملف عامة.
قيمة true تعني أنه يتم تحميل خصائص المستند فقط من ملف عرض مشفر دون استخدام كلمة مرور.
قيمة false تعني أنه يتم تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة، وليس تحميل خصائص المستند فقط.
إذا لم يكن العرض مشفراً فإن قيمة الخاصية تكون دائماً false.
إذا لم تكن خصائص المستند لملف مشفر عامة فإن قيمة الخاصية تكون دائماً false.
إذا كان Presentation.EncryptDocumentProperties يساوي true فإن قيمة خاصية IsOnlyDocumentPropertiesLoaded تكون دائماً false.
للقراءة فقط **bool**.

### التعريف:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### انظر أيضاً
* فئة [`ProtectionManager`](/slides/python-net/ar/aspose.slides/protectionmanager)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)