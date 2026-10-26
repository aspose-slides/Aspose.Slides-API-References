---
title: ToMathArray()
second_title: Referencia de API de Aspose.Slides para C++
description: Coloca en una matriz vertical
type: docs
weight: 170
url: /es/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() método


Coloca en una matriz vertical

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### Valor de retorno

Nueva instancia del tipo [IMathArray](../../imatharray/)
## Observaciones



Ejemplo: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathArray](../../imatharray/)
* Clase [MathElementBase](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)