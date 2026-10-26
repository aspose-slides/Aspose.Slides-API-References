---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Het argument waarop het accent werd toegepast
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() methode


Het argument waarop het accent werd toegepast

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathAccent](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)