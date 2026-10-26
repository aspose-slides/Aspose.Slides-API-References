---
title: get_AllCustomXmlParts()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تُرجع جميع أجزاء البيانات المخصصة في الـ presentaion. للقراءة فقط ICustomXmlPart[].
type: docs
weight: 287
url: /ar/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() طريقة

تُرجع كل أجزاء البيانات المخصصة في العرض التقديمي. للقراءة فقط [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## ملاحظات

تُظهر الأمثلة التالية كيفية مسح جميع أجزاء XML المخصصة من PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// تكرار جميع أجزاء XML المخصصة
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ICustomXmlPart](../../icustomxmlpart/)
* فئة [Presentation](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)