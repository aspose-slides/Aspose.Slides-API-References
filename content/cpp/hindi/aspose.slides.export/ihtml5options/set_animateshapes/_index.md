---
title: set_AnimateShapes()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: Shapes animation विकल्प सेट करता है। bool लिखें।
type: docs
weight: 40
url: /hi/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) मेथड


Shapes animation option को सेट करता है। **bool** लिखें।

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## संबंधित देखें

* क्लास [IHtml5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)