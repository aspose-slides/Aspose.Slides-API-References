---
title: ToMathArray()
second_title: Referencia de la API de Aspose.Slides para C++
description: Coloca en una matriz vertical
type: docs
weight: 183
url: /es/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() método


Coloca en una matriz vertical

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
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
* Clase [IMathElement](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)