---
title: set_HideSuperscript()
second_title: Referência da API Aspose.Slides for C++
description: Ocultar sobrescrito
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/imathnaryoperatorproperties/set_hidesuperscript/
---
## IMathNaryOperatorProperties::set_HideSuperscript(bool) método


Ocultar sobrescrito

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_HideSuperscript(bool value)=0
```

## Observações


Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## Ver Também

* Classe [IMathNaryOperatorProperties](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)