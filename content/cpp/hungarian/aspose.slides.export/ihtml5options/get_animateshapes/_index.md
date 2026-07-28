---
title: get_AnimateShapes()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a formák animációs beállítását. Olvasható bool.
type: docs
weight: 27
url: /hu/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() módszer


Visszaadja a formák animációs beállítását. Olvasható **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
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

* Osztály [IHtml5Options](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)