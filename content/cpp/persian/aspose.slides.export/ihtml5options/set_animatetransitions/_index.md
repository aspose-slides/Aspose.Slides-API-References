---
title: set_AnimateTransitions()
second_title: Aspose.Slides برای C++ مرجع API
description: گزینهٔ انیمیشن انتقال‌ها را تنظیم می‌کند. مقدار bool را می‌نویسید.
type: docs
weight: 14
url: /fa/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) method


گزینهٔ انیمیشن انتقال‌ها را تنظیم می‌کند. نوع **bool** را می‌نویسید.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
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