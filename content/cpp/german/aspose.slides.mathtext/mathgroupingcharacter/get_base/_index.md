---
title: get_Base()
second_title: Aspose.Slides für C++ API-Referenz
description: Base-Argument
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathgroupingcharacter/get_base/
---
## MathGroupingCharacter::get_Base() Methode


Base Argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathGroupingCharacter::get_Base() override
```

## Hinweise


Beispiel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathGroupingCharacter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)