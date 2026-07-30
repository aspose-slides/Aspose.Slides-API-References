---
title: set_AnimateTransitions()
second_title: Aspose.Slides pro C++ API Reference
description: Nastavuje možnost animace přechodů. Zapište bool.
type: docs
weight: 14
url: /cs/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) metoda


Nastavuje možnost animace přechodů. Zapište **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
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

* Třída [IHtml5Options](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)