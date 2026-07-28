---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Znak operatora rośnie pionowo, aby dopasować się do wysokości swojego argumentu
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) metoda


Znak operatora rośnie pionowo, aby dopasować się do wysokości swojego argumentu

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
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