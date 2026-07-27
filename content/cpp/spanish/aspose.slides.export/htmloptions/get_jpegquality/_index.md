---
title: get_JpegQuality()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Solo lectura uint8_t.
type: docs
weight: 144
url: /es/aspose.slides.export/htmloptions/get_jpegquality/
---
## HtmlOptions::get_JpegQuality() método


Devuelve un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Solo lectura **uint8_t**.

```cpp
uint8_t Aspose::Slides::Export::HtmlOptions::get_JpegQuality() override
```
## Observaciones


Tiene efecto solo cuando un documento contiene imágenes JPEG.

Utilice esta propiedad para obtener o establecer la calidad de las imágenes dentro de un documento al guardarlo en formato PDF. El valor puede variar de 0 a 100 donde 0 significa la peor calidad pero la máxima compresión y 100 significa la mejor calidad pero la mínima compresión.

El valor predeterminado es **95**.
## Véase también

* Clase [HtmlOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)