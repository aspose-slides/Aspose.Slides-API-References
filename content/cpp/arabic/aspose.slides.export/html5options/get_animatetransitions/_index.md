---
title: get_AnimateTransitions()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع خيار تحريك الانتقالات. قراءة bool.
type: docs
weight: 1
url: /ar/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() طريقة


يرجع خيار تحريك الانتقالات. قراءة **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## ملاحظات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## انظر أيضاً

* الفئة [Html5Options](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)