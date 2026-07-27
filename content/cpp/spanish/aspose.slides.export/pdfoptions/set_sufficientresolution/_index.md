---
title: set_SufficientResolution()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece un valor que determina la resolución de las imágenes dentro del documento PDF.
type: docs
weight: 365
url: /es/aspose.slides.export/pdfoptions/set_sufficientresolution/
---
## PdfOptions::set_SufficientResolution(float) method


Establece un valor que determina la resolución de las imágenes dentro del documento PDF.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SufficientResolution(float value) override
```

## Observaciones


La propiedad afecta al tamaño del archivo, al tiempo de exportación y a la calidad de la imagen.

El valor predeterminado es **96**.

El efecto de este parámetro depende de varios factores. El algoritmo intenta obtener el mejor tamaño de imagen de salida según el valor de la propiedad, el tamaño de la imagen fuente y el tamaño del marco de la imagen. El uso de valores de propiedad similares puede dar el mismo resultado. Se recomienda usar un paso de 16 o 32 para obtener un efecto visible.

Escriba **float**. 
## Ver también

* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)