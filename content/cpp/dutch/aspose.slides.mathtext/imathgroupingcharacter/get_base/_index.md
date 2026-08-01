---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Base-argument
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathgroupingcharacter/get_base/
---
## IMathGroupingCharacter::get_Base() methode

Base-argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathGroupingCharacter::get_Base()=0
```

## Opmerkingen

Voorbeeld: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)