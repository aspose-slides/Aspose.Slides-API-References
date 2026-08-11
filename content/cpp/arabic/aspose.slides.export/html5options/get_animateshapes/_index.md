---
title: get_AnimateShapes()
second_title: مرجع API لـ Aspose.Slides لـ C++
description: يرجع خيار تحريك الأشكال. قراءة bool.
type: docs
weight: 27
url: /ar/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() طريقة


يرجع خيار تحريك الأشكال. قراءة **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## ملاحظات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## انظر أيضًا

* فئة [Html5Options](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)