---
title: set_AnimateTransitions()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: ट्रांज़िशन एनीमेशन विकल्प सेट करता है। bool लिखें।
type: docs
weight: 14
url: /hi/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) विधि


ट्रांज़िशन एनीमेशन विकल्प सेट करता है। लिखें **bool**।

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## देखें

* क्लास [Html5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)