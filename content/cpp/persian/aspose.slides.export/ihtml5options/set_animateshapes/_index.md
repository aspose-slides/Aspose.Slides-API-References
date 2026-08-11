---
title: set_AnimateShapes()
second_title: Aspose.Slides برای C++ مرجع API
description: گزینهٔ انیمیشن اشکال را تنظیم می‌کند. مقدار bool را بنویسید.
type: docs
weight: 40
url: /fa/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) متد

گزینهٔ انیمیشن اشکال را تنظیم می‌کند. مقدار **bool** را بنویسید.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
```

## ملاحظات

مثال:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```

## موارد مرتبط

* کلاس [IHtml5Options](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)