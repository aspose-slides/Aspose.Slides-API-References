---
title: set_AnimateShapes()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Animationsoption für Formen. Schreiben bool.
type: docs
weight: 40
url: /de/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) Methode

Setzt die Animationsoption für Formen. Schreiben **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
```

## Bemerkungen


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