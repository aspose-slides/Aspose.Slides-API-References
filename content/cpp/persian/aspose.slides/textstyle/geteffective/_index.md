---
title: GetEffective()
second_title: Aspose.Slides برای C++ مرجع API
description: داده‌های قالب‌بندی سبک متن مؤثر را با اعمال وراثت دریافت می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() متد

داده‌های قالب‌بندی سبک متن مؤثر را با اعمال وراثت دریافت می‌کند.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```

### مقدار بازگشت

یک [ITextStyleEffectiveData](../../itextstyleeffectivedata/).

## ملاحظات

این مثال نشان می‌دهد که چگونه برخی از ویژگی‌های مؤثر سبک متن دریافت می‌شوند.
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

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* کلاس [TextStyle](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)