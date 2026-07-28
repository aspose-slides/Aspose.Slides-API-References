---
title: set_AnimateTransitions()
second_title: Aspose.Slides C++ API Referenciája
description: Beállítja a tranzíciók animációs opcióját. Írja bool.
type: docs
weight: 14
url: /hu/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) metódus


Beállítja a tranzíciók animációs opcióját. Írja **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
```

## Megjegyzések


Példa: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Lásd még

* Osztály [IHtml5Options](../)
* Névtere [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)