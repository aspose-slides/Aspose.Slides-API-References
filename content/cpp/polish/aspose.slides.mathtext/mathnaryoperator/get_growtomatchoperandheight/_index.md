---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Znak operatora rośnie pionowo, aby dopasować się do wysokości swojego operandu
type: docs
weight: 92
url: /pl/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() metoda

Znak operatora rośnie pionowo, aby dopasować się do wysokości swojego operandu

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## Uwagi

Przykład:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Zobacz także

* Klasa [MathNaryOperator](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)