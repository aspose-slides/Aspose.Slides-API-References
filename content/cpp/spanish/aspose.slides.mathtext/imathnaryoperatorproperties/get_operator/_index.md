---
title: get_Operator()
second_title: Referencia de API de Aspose.Slides para C++
description: "Carácter del operador N-ario Por ejemplo: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() método


Carácter del operador N-ario Por ejemplo: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
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