---
title: set_AnimateShapes()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط خيار تحريك الأشكال. اكتب bool.
type: docs
weight: 40
url: /ar/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) طريقة


يضبط خيار تحريك الأشكال. اكتب **bool**.

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




## انظر أيضًا

* الفئة [IHtml5Options](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)