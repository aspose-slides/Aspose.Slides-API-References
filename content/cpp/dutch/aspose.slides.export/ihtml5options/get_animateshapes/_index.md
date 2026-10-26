---
title: get_AnimateShapes()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de optie voor animatie van vormen. Leest bool.
type: docs
weight: 27
url: /nl/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() methode


Retourneert de optie voor animatie van vormen. Leest **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
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