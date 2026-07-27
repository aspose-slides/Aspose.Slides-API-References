---
title: get_SufficientResolution()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un valor que determina la resolución de las imágenes dentro del documento PDF.
type: docs
weight: 352
url: /es/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() método


Devuelve un valor que determina la resolución de las imágenes dentro del documento PDF.

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## Observaciones


La propiedad afecta al tamaño del archivo, al tiempo de exportación y a la calidad de la imagen.

El valor predeterminado es **96**.

El efecto de este parámetro depende de algunos factores. El algoritmo intenta obtener el mejor tamaño de imagen de salida según el valor de la propiedad, el tamaño de la imagen de origen y el tamaño del marco de la imagen. El uso de valores de propiedad similares puede dar el mismo resultado. Se recomienda usar un paso de 16 o 32 para obtener un efecto visible.

Leer **float**. 
## Ver también

* Clase [PdfOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)