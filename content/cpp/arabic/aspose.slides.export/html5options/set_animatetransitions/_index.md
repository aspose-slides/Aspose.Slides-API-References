---
title: set_AnimateTransitions()
second_title: مرجع API Aspose.Slides للغة C++
description: يضبط خيار تحريك الانتقالات. اكتب bool.
type: docs
weight: 14
url: /ar/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) طريقة

يضبط خيار تحريك الانتقالات. اكتب **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
```

## ملاحظات

مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```

## انظر أيضًا

* فئة [Html5Options](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)