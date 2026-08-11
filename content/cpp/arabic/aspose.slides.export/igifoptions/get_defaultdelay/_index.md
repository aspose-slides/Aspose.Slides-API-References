---
title: get_DefaultDelay()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يحصل على وقت التأخير الافتراضي [ms]. سيتم استخدام هذه القيمة إذا لم يتم استدعاء طريقة ISlideShowTransition::set_AdvanceAfterTime(). القيمة الافتراضية هي 1000."
type: docs
weight: 79
url: /ar/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() method


يحصل على وقت التأخير الافتراضي [ms]. سيتم استخدام هذه القيمة إذا لم يتم استدعاء طريقة [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/). القيمة الافتراضية هي 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## انظر أيضًا

* الفئة [IGifOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)