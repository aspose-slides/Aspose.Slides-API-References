---
title: set_HideSubscript()
second_title: Referência da API Aspose.Slides para C++
description: Ocultar subscrito
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/imathnaryoperatorproperties/set_hidesubscript/
---
## IMathNaryOperatorProperties::set_HideSubscript(bool) método


Ocultar subscrito

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_HideSubscript(bool value)=0
```

## Observações


Exemplo:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## Veja também

* Classe [IMathNaryOperatorProperties](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)