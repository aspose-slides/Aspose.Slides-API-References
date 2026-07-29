---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Basargument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathgroupingcharacter/get_base/
---
## MathGroupingCharacter::get_Base() metod


Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathGroupingCharacter::get_Base() override
```

## Anmärkningar


Exempel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathGroupingCharacter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)