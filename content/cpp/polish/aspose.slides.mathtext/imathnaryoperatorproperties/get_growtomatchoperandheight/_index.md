---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Znak operatora rośnie pionowo, aby dopasować się do wysokości operandu
type: docs
weight: 53
url: /pl/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() metoda


Znak operatora rośnie pionowo, aby dopasować się do wysokości operandu

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## Uwagi


Przykład: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Zobacz także

* Klasa [IMathNaryOperatorProperties](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)