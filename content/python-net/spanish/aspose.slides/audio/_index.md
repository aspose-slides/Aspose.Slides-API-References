---
title: Audio class
second_title: Aspose.Slides para Python a través de la API .NET
description: 
type: docs
url: /es/aspose.slides/audio/
---
## Clase Audio

Representa un archivo de audio incrustado.

El tipo Audio expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/es/aspose.slides/audio/content_type/) | Devuelve un tipo MIME de un audio, codificado en [`Audio.binary_data`](/slides/python-net/es/aspose.slides/audio/binary_data).<br/>            Solo lectura **str**. |
| [`binary_data`](/slides/python-net/es/aspose.slides/audio/binary_data/) | Devuelve una copia de los datos de un audio. En caso de una gran cantidad de datos, considere <br/>            usar el método [`Audio.get_stream`](/slides/python-net/es/aspose.slides/audio/get_stream) para evitar la carga innecesaria de los datos del audio<br/>            en memoria o incluso una OutOfMemoryException.<br/>            Solo lectura **int**[]. |

## Métodos

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/es/aspose.slides/audio/get_stream/#) | Devuelve un flujo Stream para leer.<br/>            Use 'using' o cierre el flujo después de usarlo. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)