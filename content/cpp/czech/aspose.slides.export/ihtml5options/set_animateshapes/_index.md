---
title: set_AnimateShapes()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastavuje volbu animace tvarů. Zapište bool.
type: docs
weight: 40
url: /cs/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) metoda


Nastavuje volbu animace tvarů. Zapište **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
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

* Třída [IHtml5Options](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)