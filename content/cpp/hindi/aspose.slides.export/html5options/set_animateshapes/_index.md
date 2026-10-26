---
title: set_AnimateShapes()
second_title: Aspose.Slides for C++ API संदर्भ
description: Shapes एनीमेशन विकल्प सेट करता है। bool लिखें।
type: docs
weight: 40
url: /hi/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) विधि

Shapes एनीमेशन विकल्प सेट करता है। लिखें **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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

* क्लास [Html5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)