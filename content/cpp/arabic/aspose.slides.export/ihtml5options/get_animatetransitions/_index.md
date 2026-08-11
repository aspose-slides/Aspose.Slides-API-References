---
title: get_AnimateTransitions()
second_title: مرجع API Aspose.Slides للـ C++
description: إرجاع خيار تحريك الانتقالات. قراءة bool.
type: docs
weight: 1
url: /ar/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() طريقة


إرجاع خيار تحريك الانتقالات. قراءة **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
```

## ملاحظات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## انظر أيضا

* الفئة [IHtml5Options](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)