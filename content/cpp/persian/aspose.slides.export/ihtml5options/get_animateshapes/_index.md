---
title: get_AnimateShapes()
second_title: مرجع API Aspose.Slides برای C++
description: گزینهٔ انیمیشن اشکال را برمی‌گرداند. bool فقط‌خواندنی است.
type: docs
weight: 27
url: /fa/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() متد


گزینهٔ انیمیشن اشکال را برمی‌گرداند. **bool** خواندنی است.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
```

## ملاحظات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## مراجع

* کلاس [IHtml5Options](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)