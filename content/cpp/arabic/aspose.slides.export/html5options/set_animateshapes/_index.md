---
title: set_AnimateShapes()
second_title: Aspose.Slides لمرجع API C++
description: يضبط خيار تحريك الأشكال. اكتب bool.
type: docs
weight: 40
url: /ar/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) طريقة

يضبط خيار تحريك الأشكال. اكتب **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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

* الفئة [Html5Options](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)