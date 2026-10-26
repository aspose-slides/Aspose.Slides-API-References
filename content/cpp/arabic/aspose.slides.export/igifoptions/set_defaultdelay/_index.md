---
title: set_DefaultDelay()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يضبط وقت التأخير الافتراضي [ms]. سيتم استخدام هذه القيمة إذا لم يتم استدعاء طريقة ISlideShowTransition::set_AdvanceAfterTime(). القيمة الافتراضية هي 1000."
type: docs
weight: 92
url: /ar/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) طريقة

يضبط وقت التأخير الافتراضي [ms]. سيتم استخدام هذه القيمة إذا لم يتم استدعاء طريقة [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/). القيمة الافتراضية هي 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## انظر أيضًا

* فئة [IGifOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)