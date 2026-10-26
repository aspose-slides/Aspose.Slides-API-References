---
title: get_Base()
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: Argument Base
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathgroupingcharacter/get_base/
---
## MathGroupingCharacter::get_Base() metoda

Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathGroupingCharacter::get_Base() override
```

## Poznámky

Příklad:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)