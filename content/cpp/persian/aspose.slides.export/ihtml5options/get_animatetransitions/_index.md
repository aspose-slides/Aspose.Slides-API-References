---
title: get_AnimateTransitions()
second_title: مرجع API Aspose.Slides برای C++
description: گزینه انیمیشن انتقال‌ها را برمی‌گرداند. مقدار bool را می‌خواند.
type: docs
weight: 1
url: /fa/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() متد

گزینهٔ انیمیشن انتقال‌ها را برمی‌گرداند. مقدار **bool** را می‌خواند.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
```

## توضیحات

مثال:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```

## موارد مرتبط

* کلاس [IHtml5Options](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)