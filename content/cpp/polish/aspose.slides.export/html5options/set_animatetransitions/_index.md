---
title: set_AnimateTransitions()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia opcję animacji przejść. Zapisz bool.
type: docs
weight: 14
url: /pl/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) metoda


Ustawia opcję animacji przejść. Zapisz **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
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

* Klasa [Html5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)