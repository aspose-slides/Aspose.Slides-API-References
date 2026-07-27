---
title: get_Superscript()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica un argumento de superíndice que, por ejemplo, en el caso de una integral, establece el límite superior
type: docs
weight: 27
url: /es/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() método

Especifica un argumento de superíndice que, por ejemplo, en el caso de una integral, establece el límite superior

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## Observaciones

Ejemplo:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathNaryOperator](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)