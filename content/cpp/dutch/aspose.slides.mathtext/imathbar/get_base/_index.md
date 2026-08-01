---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Base-argument
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() methode


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBar::get_Base()=0
```

## Opmerkingen


Voorbeeld:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathBar](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)