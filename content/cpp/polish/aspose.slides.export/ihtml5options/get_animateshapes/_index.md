---
title: get_AnimateShapes()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca opcję animacji kształtów. Odczyt bool.
type: docs
weight: 27
url: /pl/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() metoda

Zwraca opcję animacji kształtów. Odczyt **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
```

## Uwagi

Przykład:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```

## Zobacz także

* Klasa [IHtml5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)