---
title: get_HideSubscript()
second_title: Aspose.Slides für C++ API-Referenz
description: Subscript ausblenden
type: docs
weight: 118
url: /de/aspose.slides.mathtext/mathnaryoperator/get_hidesubscript/
---
## MathNaryOperator::get_HideSubscript() Methode


Subscript ausblenden

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSubscript() override
```

## Hinweise


Beispiel:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## Siehe auch

* Klasse [MathNaryOperator](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)