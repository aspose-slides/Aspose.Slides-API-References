---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Znak operatora rośnie pionowo, aby dopasować się do wysokości swojego operandu
type: docs
weight: 105
url: /pl/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) metoda


Znak operatora rośnie pionowo, aby dopasować się do wysokości swojego operandu

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## Uwagi


Przykład: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Patrz też

* Klasa [MathNaryOperator](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)