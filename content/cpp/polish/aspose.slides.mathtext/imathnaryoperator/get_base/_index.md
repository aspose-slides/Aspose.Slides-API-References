---
title: get_Base()
second_title: Aspose.Slides – odniesienie API dla C++
description: Argument bazowy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathnaryoperator/get_base/
---
## IMathNaryOperator::get_Base() metoda


Argument bazowy

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Base()=0
```

## Uwagi


Przykład: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathNaryOperator](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)