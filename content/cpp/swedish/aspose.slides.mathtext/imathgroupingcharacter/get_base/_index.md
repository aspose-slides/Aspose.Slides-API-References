---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Basargument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathgroupingcharacter/get_base/
---
## IMathGroupingCharacter::get_Base() metod


Basargument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathGroupingCharacter::get_Base()=0
```

## Anmärkningar


Exempel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathGroupingCharacter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)