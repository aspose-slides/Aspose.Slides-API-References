---
title: get_AnimateTransitions()
second_title: Aspose.Slides dla C++ – odwołanie API
description: Zwraca opcję animacji przejść. Odczyt bool.
type: docs
weight: 1
url: /pl/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() metoda


Zwraca opcję animacji przejść. Odczyt **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## Uwagi


Przykład: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Zobacz też

* Klasa [Html5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)