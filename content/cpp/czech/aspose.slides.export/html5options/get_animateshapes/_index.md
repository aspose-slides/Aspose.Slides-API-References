---
title: get_AnimateShapes()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vrací možnost animace tvarů. Čte bool.
type: docs
weight: 27
url: /cs/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() metoda


Vrací volbu animace tvarů. Čte **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## Poznámky


Příklad: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Viz také

* Třída [Html5Options](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)