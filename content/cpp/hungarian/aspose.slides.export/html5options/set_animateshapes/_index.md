---
title: set_AnimateShapes()
second_title: Aspose.Slides C++ API referenciája
description: Beállítja az alakzatok animációs opcióját. Írja bool.
type: docs
weight: 40
url: /hu/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) metódus


Beállítja az alakzatok animációs opcióját. Írja **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)