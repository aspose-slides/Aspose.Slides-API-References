---
title: get_AnimateShapes()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja a formák animációs beállítását. Olvasás bool.
type: docs
weight: 27
url: /hu/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() metódus


Visszaadja a formák animációs beállítását. Olvasás **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## Megjegyzések


Példa: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Lásd még

* Osztály [Html5Options](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)