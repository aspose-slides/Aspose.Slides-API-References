---
title: get_AnimateTransitions()
second_title: Aspose.Slides for C++ API referenciája
description: Visszaadja az átmenetek animációjának beállítását. Olvasás típusa bool.
type: docs
weight: 1
url: /hu/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() metódus

Visszaadja az átmenetek animációjának beállítását. Olvasás típusa **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
```

## Megjegyzések

Példa:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```

## Lásd még

* Osztály [IHtml5Options](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)