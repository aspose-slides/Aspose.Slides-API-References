---
title: get_AnimateTransitions()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: ट्रांज़िशन एनीमेशन विकल्प को लौटाता है। पढ़ें bool.
type: docs
weight: 1
url: /hi/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() विधि

ट्रांज़िशन एनीमेशन विकल्प को वापस करता है। पढ़ें **bool**।

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
```

## टिप्पणी

उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```

## संबंधित देखें

* क्लास [IHtml5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)