---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Basisargument
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathborderbox/get_base/
---
## IMathBorderBox::get_Base() methode


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBorderBox::get_Base()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
auto baseArg = borderBox->get_Base();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathBorderBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)