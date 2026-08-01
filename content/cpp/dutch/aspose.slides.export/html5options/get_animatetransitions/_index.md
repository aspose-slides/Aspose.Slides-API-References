---
title: get_AnimateTransitions()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de optie voor overgangsanimatie. Lees bool.
type: docs
weight: 1
url: /nl/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() methode


Retourneert de optie voor overgangsanimatie. Lees **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Zie ook

* Klasse [Html5Options](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)