---
title: GetVisualBounds()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado.
type: docs
weight: 677
url: /es/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() método

Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```

### Valor de retorno

Un [System::Drawing::RectangleF](../../../system.drawing/rectanglef/) que representa los límites visuales de la forma en coordenadas de diapositiva.
## Observaciones

El rectángulo devuelto representa los límites alineados a los ejes de todo el contenido producido por la forma durante el renderizado en el espacio de coordenadas de la diapositiva.

Estos límites pueden diferir de los límites del modelo de la forma ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) y pueden contener coordenadas negativas si el contenido renderizado se extiende más allá del origen de la diapositiva.

Los límites visuales tienen en cuenta aspectos relacionados con el renderizado, como transformaciones (por ejemplo, rotación), ancho y uniones del trazo, disposición y desbordamiento del texto, [SmartArt](../../../aspose.slides.smartart/) geometría, y otros efectos de disposición que influyen en la apariencia final renderizada de la forma.

Los límites devueltos no están recortados al rectángulo de la diapositiva. 

## Ver también

* Clase [RectangleF](../../../system.drawing/rectanglef/)
* Clase [Shape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)