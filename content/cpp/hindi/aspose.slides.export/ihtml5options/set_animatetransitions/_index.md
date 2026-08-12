---
title: set_AnimateTransitions()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ट्रांज़िशन एनीमेशन विकल्प सेट करता है। लिखें bool.
type: docs
weight: 14
url: /hi/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) विधि


ट्रांज़िशन एनीमेशन विकल्प सेट करता है। लिखें **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
```

## टिप्पणी


उदाहरण:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## देखें

* क्लास [IHtml5Options](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)