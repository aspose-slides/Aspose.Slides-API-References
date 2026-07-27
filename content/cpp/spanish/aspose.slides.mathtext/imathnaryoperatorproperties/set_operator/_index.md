---
title: set_Operator()
second_title: Aspose.Slides para la referencia de API de C++
description: "Carácter del operador nario Por ejemplo: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) método

Carácter del operador nario Por ejemplo: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## Observaciones

Ejemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Ver también

* Clase [IMathNaryOperatorProperties](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)