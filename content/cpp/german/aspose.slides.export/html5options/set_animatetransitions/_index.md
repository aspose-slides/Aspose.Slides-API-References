---
title: set_AnimateTransitions()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Option für die Übergangsanimation. Schreiben bool.
type: docs
weight: 14
url: /de/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) Methode


Setzt die Option für die Übergangsanimation. Schreiben **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
```

## Hinweise


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