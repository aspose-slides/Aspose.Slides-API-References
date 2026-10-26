---
title: get_RotationAngle()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma acompañante. Si se especifica, entonces se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Leer float.
type: docs
weight: 339
url: /es/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() método

Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma asociada. Si se especifica, entonces se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Leer **float**.

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## Observaciones

Considere el caso en el que una forma tiene una rotación de 90 grados en sentido horario aplicada a ella. Además de esto, el cuerpo del texto en sí tiene una rotación de -90 grados en sentido antihorario aplicada a él. Entonces, la forma resultante parecería estar rotada, pero el texto dentro de ella parecería como si no se hubiera rotado en absoluto.

## Ver también

* Clase [ITextFrameFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)