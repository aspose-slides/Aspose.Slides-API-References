---
title: set_RotationAngle()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica de manera personalizada la rotación que se aplica al texto dentro del recuadro delimitador. Si no se especifica, se utiliza la rotación de la forma asociada. Si se especifica, entonces se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que al propio texto se le aplique una rotación. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Escriba float.
type: docs
weight: 313
url: /es/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) método


Especifica de manera personalizada la rotación que se aplica al texto dentro del recuadro delimitador. Si no se especifica, se utiliza la rotación de la forma asociada. Si se especifica, entonces se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que al propio texto se le aplique una rotación. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Escriba **float**.

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## Observaciones


Considere el caso en el que una forma tiene una rotación de 90 grados en sentido horario aplicada a ella. Además de esto, el cuerpo del texto en sí tiene una rotación de -90 grados en sentido antihorario aplicada a él. Entonces, la forma resultante parecería estar rotada, pero el texto dentro de ella parecería como si no se hubiera rotado en absoluto. 
## Ver también

* Clase [TextFrameFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)