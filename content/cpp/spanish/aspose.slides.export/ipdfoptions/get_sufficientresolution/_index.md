---
title: get_SufficientResolution()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un valor que determina la resolución de las imágenes dentro del documento PDF.
type: docs
weight: 313
url: /es/aspose.slides.export/ipdfoptions/get_sufficientresolution/
---
## IPdfOptions::get_SufficientResolution() método

Devuelve un valor que determina la resolución de las imágenes dentro del documento PDF.

```cpp
virtual float Aspose::Slides::Export::IPdfOptions::get_SufficientResolution()=0
```

## Observaciones

La propiedad afecta al tamaño del archivo, al tiempo de exportación y a la calidad de la imagen.

El valor predeterminado es **96**.

El efecto de este parámetro depende de varios factores. El algoritmo intenta obtener el mejor tamaño de imagen de salida según el valor de la propiedad, el tamaño de la imagen original y el tamaño del marco de la imagen. El uso de valores de propiedad similares puede dar el mismo resultado. Se recomienda usar un paso de 16 o 32 para obtener un efecto visible.

Lectura **float**. 
## Ver también

* Clase [IPdfOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)