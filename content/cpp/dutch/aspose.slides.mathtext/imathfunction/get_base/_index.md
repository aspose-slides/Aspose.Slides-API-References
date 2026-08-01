---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Functieargument
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() methode


Functieargument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
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
* Klasse [IMathFunction](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)