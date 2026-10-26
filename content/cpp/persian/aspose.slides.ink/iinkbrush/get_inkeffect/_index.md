---
title: get_InkEffect()
second_title: Aspose.Slides برای C++ مرجع API
description: "نوع اثر جوهر (به عنوان مثال Galaxy, Gold, Silver) را که سبک بصری ضربه جوهر را تعریف می‌کند، دریافت می‌کند. مقدار از ویژگی براش \"inkEffects\" تجزیه می‌شود. اگر هیچ اثر شناخته‌شده‌ای مشخص نشده باشد، InkEffectType::NotDefined برگردانده می‌شود."
type: docs
weight: 53
url: /fa/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() متد

نوع اثر جوهر (مانند Galaxy, Gold, Silver) را که سبک بصری ضربه جوهر را تعریف می‌کند، دریافت می‌کند. مقدار از ویژگی براش \"inkEffects\" تجزیه می‌شود. اگر هیچ اثر شناسایی‌شده‌ای مشخص نشده باشد، [InkEffectType::NotDefined](../../inkeffecttype/) برگردانده می‌شود.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## موارد مرتبط

* شمارش [InkEffectType](../../inkeffecttype/)
* کلاس [IInkBrush](../)
* فضاينام [Aspose::Slides::Ink](../../)
* کتابخانه [Aspose.Slides](../../../)