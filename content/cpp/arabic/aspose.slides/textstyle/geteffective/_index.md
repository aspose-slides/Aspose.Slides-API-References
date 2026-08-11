---
title: GetEffective()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على بيانات تنسيق نمط النص الفعّال مع تطبيق الوراثة.
type: docs
weight: 27
url: /ar/aspose.slides/textstyle/geteffective/
---
## طريقة TextStyle::GetEffective()

يحصل على بيانات تنسيق نمط النص الفعّال مع تطبيق الوراثة.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```

### قيمة الإرجاع

[ITextStyleEffectiveData](../../itextstyleeffectivedata/).

## ملاحظات

يوضح هذا المثال الحصول على بعض خصائص نمط النص الفعّال.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* فئة [TextStyle](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)