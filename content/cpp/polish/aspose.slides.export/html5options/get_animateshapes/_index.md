---
title: get_AnimateShapes()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca opcję animacji kształtów. Odczyt bool.
type: docs
weight: 27
url: /pl/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() metoda


Zwraca opcję animacji kształtów. Odczyt **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
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

* Klasa [Html5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)