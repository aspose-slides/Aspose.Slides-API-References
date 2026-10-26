---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Het argument waarop het accent werd toegepast
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() methode


Het argument waarop het accent werd toegepast

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
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
* Klasse [MathAccent](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)