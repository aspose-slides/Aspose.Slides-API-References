---
title: get_RotationAngle()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica de forma personalizada la rotación que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma acompañante. Si se especifica, entonces se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Leer float.
type: docs
weight: 300
url: /es/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() method

Especifica de forma personalizada la rotación que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma acompañante. Si se especifica, entonces se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Leer **float**.

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## Observaciones

Considere el caso en que una forma tiene una rotación de 90 grados en sentido horario aplicada. Además de esto, el propio cuerpo de texto tiene una rotación de -90 grados en sentido antihorario aplicada. Entonces la forma resultante aparecería rotada pero el texto dentro de ella parecería no haber sido rotado en absoluto. 

## Véase también

* Clase [TextFrameFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)