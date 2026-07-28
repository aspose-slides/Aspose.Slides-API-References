---
title: get_AnimateTransitions()
second_title: Aspose.Slides for C++ API referencia
description: Visszaadja az átmenetek animációs beállítását. Olvasás bool.
type: docs
weight: 1
url: /hu/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() metódus


Visszaadja az átmenetek animációs beállítását. Olvasás **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
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

* Osztály [Html5Options](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)