---
title: get_AnimateTransitions()
second_title: مرجع API Aspose.Slides برای C++
description: گزینهٔ انیمیشن انتقال‌ها را برمی‌گرداند. خواندنی bool.
type: docs
weight: 1
url: /fa/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() متد

گزینهٔ انیمیشن انتقال‌ها را برمی‌گرداند. خواندنی **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
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

* کلاس [Html5Options](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)