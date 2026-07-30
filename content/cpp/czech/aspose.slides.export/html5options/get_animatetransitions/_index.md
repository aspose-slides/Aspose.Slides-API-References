---
title: get_AnimateTransitions()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací možnost animace přechodů. Čte bool.
type: docs
weight: 1
url: /cs/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() metoda


Vrací možnost animace přechodů. Čte **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## Poznámky


Příklad:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Viz také

* Třída [Html5Options](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)