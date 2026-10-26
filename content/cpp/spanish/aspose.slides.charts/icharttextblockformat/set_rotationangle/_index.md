---
title: set_RotationAngle()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica la rotación personalizada que se está aplicando al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma acompañante. Si se especifica, entonces esto se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada. El valor resultante de la rotación visual del texto, resumido a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Escribe float.
type: docs
weight: 248
url: /es/aspose.slides.charts/icharttextblockformat/set_rotationangle/
---
## IChartTextBlockFormat::set_RotationAngle(float) método


Especifica la rotación personalizada que se está aplicando al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma acompañante. Si se especifica, entonces esto se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada. El valor resultante de la rotación visual del texto, resumido a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Escribe **float**.

```cpp
virtual void Aspose::Slides::Charts::IChartTextBlockFormat::set_RotationAngle(float value)=0
```

## Observaciones


Considere el caso en el que una forma tiene una rotación de 90 grados en sentido horario aplicada a ella. Además de esto, el cuerpo del texto tiene una rotación de -90 grados en sentido antihorario aplicada a él. Entonces la forma resultante parecería rotada, pero el texto dentro de ella parecería como si no hubiera sido rotado en absoluto. 
## Véase también

* Clase [IChartTextBlockFormat](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)