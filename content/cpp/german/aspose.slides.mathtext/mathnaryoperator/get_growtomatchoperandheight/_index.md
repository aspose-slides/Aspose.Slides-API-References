---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides für C++ API-Referenz
description: Operatorzeichen wächst vertikal, um die Höhe des Operanden anzupassen
type: docs
weight: 92
url: /de/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() Methode


Operatorzeichen wächst vertikal, um die Höhe des Operanden anzupassen

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## Hinweise


Beispiel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Siehe auch

* Klasse [MathNaryOperator](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)