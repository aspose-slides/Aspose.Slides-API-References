---
title: get_DefaultDelay()
second_title: مرجع API Aspose.Slides للغة C++
description: "يسترجع وقت التأخير الافتراضي [ms]. سيتم استخدام هذه القيمة إذا لم يتم استدعاء طريقة ISlideShowTransition::set_AdvanceAfterTime(). القيمة الافتراضية هي 1000."
type: docs
weight: 79
url: /ar/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() طريقة

يسترجع وقت التأخير الافتراضي [ms]. سيتم استخدام هذه القيمة إذا لم يتم استدعاء طريقة [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/). القيمة الافتراضية هي 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## أنظر أيضًا

* الفئة [GifOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)