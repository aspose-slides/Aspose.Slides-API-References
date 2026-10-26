---
title: set_AnimateTransitions()
second_title: مرجع API Aspose.Slides برای C++
description: گزینهٔ انیمیشن انتقال‌ها را تنظیم می‌کند. مقدار bool را بنویسید.
type: docs
weight: 14
url: /fa/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) متد

گزینهٔ انیمیشن انتقال‌ها را تنظیم می‌کند. مقدار **bool** را بنویسید.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
```

## توضیحات

مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```

## مراجع

* کلاس [Html5Options](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)