---
title: GetEffective()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة.
type: docs
weight: 391
url: /ar/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() طريقة

يحصل على بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### قيمة الإرجاع

كائن [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## ملاحظات



يوضح هذا المثال كيفية الحصول على بعض خصائص تنسيق إطار النص الفعّالة. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* فئة [TextFrameFormat](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)