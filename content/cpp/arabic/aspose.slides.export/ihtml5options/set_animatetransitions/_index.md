---
title: set_AnimateTransitions()
second_title: Aspose.Slides لـ C++ مرجع API
description: يضبط خيار الرسوم المتحركة للانتقالات. اكتب bool.
type: docs
weight: 14
url: /ar/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) طريقة


يضبط خيار الرسوم المتحركة للانتقالات. اكتب **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
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

* الفئة [IHtml5Options](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)