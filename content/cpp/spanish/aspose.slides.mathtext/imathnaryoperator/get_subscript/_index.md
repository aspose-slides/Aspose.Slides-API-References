---
title: get_Subscript()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica un argumento de subíndice que, por ejemplo, en el caso de una integral, establece el límite inferior
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() método

Especifica un argumento de subíndice que, por ejemplo, en el caso de una integral, establece el límite inferior

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## Observaciones

Ejemplo:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathNaryOperator](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)