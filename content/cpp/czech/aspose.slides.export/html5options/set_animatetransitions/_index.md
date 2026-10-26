---
title: set_AnimateTransitions()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Nastavuje možnost animace přechodů. Zapište bool.
type: docs
weight: 14
url: /cs/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) metoda


Nastavuje možnost animace přechodů. Zapište **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
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