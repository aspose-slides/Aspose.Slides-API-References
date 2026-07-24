---
title: get_AnimateShapes()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Animationsoption für Formen zurück. Lese bool.
type: docs
weight: 27
url: /de/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() Methode


Gibt die Animationsoption für Formen zurück. Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
```

## Hinweise


Beispiel: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Siehe auch

* Klasse [IHtml5Options](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)