---
title: set_AnimateShapes()
second_title: مرجع API Aspose.Slides برای C++
description: گزینهٔ انیمیشن اشکال را تنظیم می‌کند. مقدار bool را بنویسید.
type: docs
weight: 40
url: /fa/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) متد


گزینهٔ انیمیشن اشکال را تنظیم می‌کند. مقدار **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
```

## توضیحات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```


## مراجع

* کلاس [Html5Options](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)