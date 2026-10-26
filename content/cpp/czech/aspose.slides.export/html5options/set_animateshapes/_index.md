---
title: set_AnimateShapes()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Nastavuje možnost animace tvarů. Zapište bool.
type: docs
weight: 40
url: /cs/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) metoda


Nastavuje možnost animace tvarů. Zapište **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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