---
title: get_NoBreak()
second_title: Aspose.Slides voor C++ API-referentie
description: "No break. Deze eigenschap specificeert de \"unbreakable\" eigenschap op de objectdoos. Wanneer true, kunnen er geen regeleinden optreden binnen de doos. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er regeleinden optreden binnen de doos. Standaard: true"
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() methode

No break. This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## Opmerkingen

Example: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Zie ook

* Klasse [IMathBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)