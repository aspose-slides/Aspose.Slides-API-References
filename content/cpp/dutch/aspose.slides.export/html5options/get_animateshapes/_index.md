---
title: get_AnimateShapes()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de optie voor het animeren van vormen. Lezen bool.
type: docs
weight: 27
url: /nl/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() method


Retourneert de optie voor het animeren van vormen. Lezen **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Zie ook

* Klasse [Html5Options](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)