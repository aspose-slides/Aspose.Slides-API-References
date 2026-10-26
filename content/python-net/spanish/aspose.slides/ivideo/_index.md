---
title: IVideo class
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/ivideo/
---
## IVideo clase

Representa un video incrustado en una presentación.

El tipo IVideo expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`content_type`](/slides/python-net/es/aspose.slides/ivideo/content_type/) | Devuelve un tipo MIME de un video, codificado en [`IVideo.binary_data`](/slides/python-net/es/aspose.slides/ivideo/binary_data).<br/>            Solo lectura **str**. |
| [`binary_data`](/slides/python-net/es/aspose.slides/ivideo/binary_data/) | Devuelve una copia de los datos de un audio. En caso de una gran cantidad de datos, considere usar el <br/>            [`IVideo.get_stream`](/slides/python-net/es/aspose.slides/ivideo/get_stream) método para evitar la carga innecesaria de los datos del video en memoria <br/>            o incluso OutOfMemoryException.<br/>            Solo lectura **int**[]. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/es/aspose.slides/ivideo/get_stream/#) | Devuelve un Stream para lectura.<br/>            Use 'using' o cierre el stream después de usarlo. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)