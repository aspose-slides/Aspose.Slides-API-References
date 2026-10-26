---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides voor C++ API-referentie
description: Operator Character groeit verticaal om de hoogte van zijn operand te evenaren
type: docs
weight: 66
url: /nl/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) methode


Operator Character groeit verticaal om de hoogte van zijn operand te evenaren

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Zie ook

* Klasse [IMathNaryOperatorProperties](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)