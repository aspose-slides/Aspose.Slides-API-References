---
title: get_Operator()
second_title: Referencia de API de Aspose.Slides para C++
description: "Carácter de operador n-ario Por ejemplo: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() método

Carácter de operador n-ario Por ejemplo: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## Observaciones

Ejemplo:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Ver también

* Clase [MathNaryOperator](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)