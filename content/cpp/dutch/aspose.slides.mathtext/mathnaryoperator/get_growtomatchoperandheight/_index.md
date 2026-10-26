---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides voor C++ API-referentie
description: Operator-karakter groeit verticaal om de hoogte van zijn operand te evenaren
type: docs
weight: 92
url: /nl/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() methode


Operatorkarakter groeit verticaal om de hoogte van zijn operand te evenaren

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Zie ook

* Klasse [MathNaryOperator](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)