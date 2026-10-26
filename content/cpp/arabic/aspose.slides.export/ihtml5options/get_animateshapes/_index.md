---
title: get_AnimateShapes()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ C++
description: يرجع خيار تحريك الأشكال. اقرأ bool.
type: docs
weight: 27
url: /ar/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() طريقة


يرجع خيار تحريك الأشكال. اقرأ **bool**.

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




## انظر أيضًا

* فئة [IHtml5Options](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)