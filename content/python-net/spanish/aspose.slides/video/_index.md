---
title: Video class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/video/
---
## Clase Video

Representa una imagen incrustada en una presentación.

El tipo Video expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`content_type`](/slides/python-net/es/aspose.slides/video/content_type/) | Devuelve un tipo MIME de un video, codificado en [`Video.binary_data`](/slides/python-net/es/aspose.slides/video/binary_data).<br/>            Sólo lectura **str**. |
| [`binary_data`](/slides/python-net/es/aspose.slides/video/binary_data/) | Devuelve una copia de los datos de un audio. En caso de una gran cantidad de datos, considere usar el <br/>            método [`Video.get_stream`](/slides/python-net/es/aspose.slides/video/get_stream) para evitar la carga innecesaria de los datos del video en memoria <br/>            o incluso OutOfMemoryException.<br/>            Sólo lectura **int**[]. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/es/aspose.slides/video/get_stream/#) | Devuelve Stream stream para leer.<br/>            Use 'using' o cierre stream después de usarlo. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)