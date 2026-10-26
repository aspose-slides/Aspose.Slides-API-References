---
title: get_AnimateTransitions()
second_title: Aspose.Slides dla C++ Odniesienie API
description: Zwraca opcję animacji przejść. Odczyt bool.
type: docs
weight: 1
url: /pl/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() metoda


Zwraca opcję animacji przejść. Odczyt **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
```

## Uwagi


Przykład: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```



## Zobacz także

* Klasa [IHtml5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)