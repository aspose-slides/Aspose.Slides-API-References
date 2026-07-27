---
title: set_RotationAngle()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma adyacente. Si se especifica, entonces se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Escriba float.
type: docs
weight: 352
url: /es/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) method

Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma adyacente. Si se especifica, entonces se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Escriba **float**.

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## Observaciones

Considere el caso en el que una forma tiene una rotación de 90 grados en sentido horario aplicada. Además de esto, el cuerpo del texto tiene una rotación de -90 grados en sentido antihorario aplicada. Entonces, la forma resultante parecerá estar rotada, pero el texto dentro de ella aparecerá como si no hubiera sido rotado en absoluto.

## Ver también

* Clase [ITextFrameFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)