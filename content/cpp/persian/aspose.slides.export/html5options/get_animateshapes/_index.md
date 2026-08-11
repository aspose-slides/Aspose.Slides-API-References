---
title: get_AnimateShapes()
second_title: مرجع API Aspose.Slides برای C++
description: گزینهٔ انیمیشن اشکال را برمی‌گرداند. خواندنی bool.
type: docs
weight: 27
url: /fa/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() متد


گزینهٔ انیمیشن اشکال را برمی‌گرداند. خواندنی **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## توضیحات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## موارد مرتبط

* کلاس [Html5Options](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)