---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides voor C++ API-referentie
description: Operator-teken groeit verticaal zodat het overeenkomt met de hoogte van de operand
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() method


Operator-teken groeit verticaal zodat het overeenkomt met de hoogte van de operand

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
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