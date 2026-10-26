---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides für C++ API-Referenz
description: Operatorzeichen wächst vertikal, um die Höhe des Operanden anzupassen
type: docs
weight: 105
url: /de/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) Methode


Das Operatorzeichen wächst vertikal, um die Höhe des Operanden anzupassen

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## Bemerkungen


Beispiel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Siehe auch

* Klasse [MathNaryOperator](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)