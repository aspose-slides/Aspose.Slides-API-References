---
title: set_AnimateTransitions()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de animatieoptie voor overgangen in. Schrijf bool.
type: docs
weight: 14
url: /nl/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) methode


Stelt de animatie-optie voor overgangen in. Schrijf **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
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

* Klasse [IHtml5Options](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)