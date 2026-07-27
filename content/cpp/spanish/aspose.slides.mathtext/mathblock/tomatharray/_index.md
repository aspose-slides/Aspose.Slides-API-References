---
title: ToMathArray()
second_title: Referencia de API de Aspose.Slides para C++
description: Coloca los elementos hijos en una matriz vertical
type: docs
weight: 235
url: /es/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() método

Coloca los elementos hijos en una matriz vertical

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```

### Valor de retorno

Nueva instancia del tipo [IMathArray](../../imatharray/)
## Observaciones



Ejemplo:
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathArray](../../imatharray/)
* Clase [MathBlock](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)