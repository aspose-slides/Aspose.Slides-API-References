---
title: get_RotationAngle()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma adjunta. Si se especifica, entonces se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Leer float.
type: docs
weight: 235
url: /es/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() método


Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma adjunta. Si se especifica, entonces se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de la rotación que se aplique al propio texto. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Leer **float**.

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## Observaciones


Considere el caso en el que una forma tiene una rotación de 90 grados en sentido horario aplicada a ella. Además de esto, el cuerpo del texto tiene una rotación de -90 grados en sentido antihorario aplicada a él. Entonces, la forma resultante aparecería rotada pero el texto dentro de ella parecería como si no hubiera sido rotado en absoluto. 
## Ver también

* Clase [IChartTextBlockFormat](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)