---
title: GetEffective()
second_title: مرجع API Aspose.Slides لـ C++
description: يحصل على بيانات تنسيق الفقرة الفعّالة مع تطبيق الوراثة.
type: docs
weight: 365
url: /ar/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() طريقة

يحصل على بيانات تنسيق الفقرة الفعّالة مع تطبيق الوراثة.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```

### قيمة الإرجاع

قيمة [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).

## ملاحظات

يوضح هذا المثال كيفية الحصول على بعض خصائص تنسيق الفقرة الفعّالة. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* فئة [ParagraphFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)