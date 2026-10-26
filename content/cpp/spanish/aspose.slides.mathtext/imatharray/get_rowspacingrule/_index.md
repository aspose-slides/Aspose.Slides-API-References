---
title: get_RowSpacingRule()
second_title: Referencia de la API de Aspose.Slides para C++
description: El tipo de espaciado vertical entre los elementos del array
type: docs
weight: 92
url: /es/aspose.slides.mathtext/imatharray/get_rowspacingrule/
---
## IMathArray::get_RowSpacingRule() método


El tipo de espaciado vertical entre los elementos del array

```cpp
virtual MathRowSpacingRule Aspose::Slides::MathText::IMathArray::get_RowSpacingRule()=0
```

## Observaciones


Ejemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## Ver también

* Enumeración [MathRowSpacingRule](../../mathrowspacingrule/)
* Clase [IMathArray](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)