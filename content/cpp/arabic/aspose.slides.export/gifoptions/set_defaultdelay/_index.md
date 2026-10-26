---
title: set_DefaultDelay()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يضبط زمن التأخير الافتراضي [ms]. سيتم استخدام هذه القيمة إذا لم يتم استدعاء طريقة ISlideShowTransition::set_AdvanceAfterTime(). القيمة الافتراضية هي 1000."
type: docs
weight: 92
url: /ar/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) طريقة

يضبط زمن التأخير الافتراضي [ms]. سيتم استخدام هذه القيمة إذا لم يتم استدعاء طريقة [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/). القيمة الافتراضية هي 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## انظر أيضًا

* الفئة [GifOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)