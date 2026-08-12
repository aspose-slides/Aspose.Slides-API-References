---
title: get_AnimateTransitions()
second_title: Aspose.Slides for C++ API संदर्भ
description: ट्रांज़िशन एनीमेशन विकल्प लौटाता है। पढ़ें bool.
type: docs
weight: 1
url: /hi/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() विधि


ट्रांज़िशन एनीमेशन विकल्प लौटाता है। पढ़ें **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## देखें भी

* क्लास [Html5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)