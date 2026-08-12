---
title: get_AnimateShapes()
second_title: Aspose.Slides for C++ API संदर्भ
description: शेप्स एनीमेशन विकल्प लौटाता है। पढ़ें bool.
type: docs
weight: 27
url: /hi/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() मेथड


शेप्स एनीमेशन विकल्प को लौटाता है। पढ़ें **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## टिप्पणी


उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## देखें

* कक्षा [Html5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)