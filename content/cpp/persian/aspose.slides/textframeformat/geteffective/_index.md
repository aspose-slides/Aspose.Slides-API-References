---
title: GetEffective()
second_title: Aspose.Slides برای مرجع API C++
description: داده‌های قالب‌بندی مؤثر فریم متن را با اعمال ارث‌بری دریافت می‌کند.
type: docs
weight: 391
url: /fa/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() متد

Gets effective text frame formatting data with the inheritance applied.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### مقدار بازگشت

یک [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).

## توضیحات

این مثال نشان می‌دهد که چگونه برخی از ویژگی‌های قالب‌بندی مؤثر فریم متن را دریافت می‌کنیم. 
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

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* کلاس [TextFrameFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)