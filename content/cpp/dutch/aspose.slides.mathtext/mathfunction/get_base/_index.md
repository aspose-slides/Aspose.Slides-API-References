---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Functieargument
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() methode

Functieargument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathFunction](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)