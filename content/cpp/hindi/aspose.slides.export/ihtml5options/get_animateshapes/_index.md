---
title: get_AnimateShapes()
second_title: Aspose.Slides for C++ API संदर्भ
description: आकृतियों की एनीमेशन विकल्प लौटाता है। पढ़ें bool.
type: docs
weight: 27
url: /hi/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() विधि


आकृतियों की एनीमेशन विकल्प लौटाता है। पढ़ें **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## देखें

* क्लास [IHtml5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)