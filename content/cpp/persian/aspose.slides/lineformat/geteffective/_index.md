---
title: GetEffective()
second_title: Aspose.Slides برای C++، مرجع API
description: داده‌های قالب‌بندی خط مؤثر را با اعمال وراثت دریافت می‌کند.
type: docs
weight: 417
url: /fa/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() متد


داده‌های قالب‌بندی خط مؤثر را با اعمال وراثت دریافت می‌کند.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### مقدار بازگشتی

یک [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## توضیحات



این مثال نحوه دریافت ویژگی‌های مؤثر قالب خط شکل را نشان می‌دهد. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* کلاس [LineFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)