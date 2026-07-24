---
title: get_AnimateTransitions()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Animationsoption für Übergänge zurück. Lese bool.
type: docs
weight: 1
url: /de/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() Methode


Gibt die Animationsoption für Übergänge zurück. Lesen **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## Bemerkungen


Beispiel: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Siehe auch

* Klasse [Html5Options](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)