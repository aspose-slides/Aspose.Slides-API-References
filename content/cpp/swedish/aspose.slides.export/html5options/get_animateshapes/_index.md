---
title: get_AnimateShapes()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alternativ för formanimation. Läs **bool**.
type: docs
weight: 27
url: /sv/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() metod


Returnerar alternativ för formanimation. Läs **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## Anmärkningar


Exempel: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Se också

* Klass [Html5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)