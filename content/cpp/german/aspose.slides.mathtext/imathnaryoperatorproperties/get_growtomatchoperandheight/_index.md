---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides für C++ API-Referenz
description: Operatorzeichen wächst vertikal, um die Höhe seines Operanden anzupassen
type: docs
weight: 53
url: /de/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() Methode


Operatorzeichen wächst vertikal, um die Höhe seines Operanden anzupassen

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## Hinweise


Beispiel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Siehe auch

* Klasse [IMathNaryOperatorProperties](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)