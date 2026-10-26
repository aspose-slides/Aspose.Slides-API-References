---
title: get_PathTypes()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene una matriz de valores byte que especifican el tipo de cada punto en la ruta del elemento.
type: docs
weight: 27
url: /es/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() método

Obtiene una matriz de valores byte que especifican el tipo de cada punto en la ruta del elemento.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```
## Observaciones

**0** Indica que el punto es el inicio de una figura.

**1** Indica que el punto es uno de los dos extremos de una línea.

**3** Indica que el punto es un extremo o un punto de control de una spline cúbica de Bézier.

**7** Enmascara todos los bits excepto los tres bits de menor orden, que indican el tipo de punto.

**16** Especifica que el segmento correspondiente está traceado.

**32** Especifica que el punto es un marcador.

**128** Especifica que el punto es el último punto en una subruta cerrada (figura).

**129** Indica un punto de datos que es tanto un extremo de un segmento de línea como el último punto de una subruta cerrada.
## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ShapeElement](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)