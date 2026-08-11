---
title: GetEffective()
second_title: مرجع API Aspose.Slides برای C++
description: داده‌های قالب‌بندی بخش مؤثر را با اعمال وراثت دریافت می‌کند.
type: docs
weight: 131
url: /fa/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() متد

داده‌های قالب‌بندی بخش مؤثر را با اعمال وراثت دریافت می‌کند.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```

### مقدار بازگشت

یک [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## توضیحات



این مثال نشان می‌دهد که چگونه برخی از ویژگی‌های قالب‌بندی بخش مؤثر را دریافت کنیم.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* کلاس [PortionFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)