---
title: set_AnimateShapes()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de animatieoptie voor vormen in. Schrijf bool.
type: docs
weight: 40
url: /nl/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) methode


Stelt de animatieoptie voor vormen in. Schrijf **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
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

* Klasse [IHtml5Options](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)