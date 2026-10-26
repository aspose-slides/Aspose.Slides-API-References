---
title: get_AnimateShapes()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Animationsoption für Formen zurück. Lese bool.
type: docs
weight: 27
url: /de/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() Methode


Gibt die Animationsoption für Formen zurück. Lese **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
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

* Klasse [Html5Options](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)