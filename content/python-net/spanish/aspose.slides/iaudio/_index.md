---
title: IAudio class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/iaudio/
---
## IAudio clase

Representa un archivo de audio incrustado.

El tipo IAudio expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`content_type`](/slides/python-net/es/aspose.slides/iaudio/content_type/) | Devuelve un tipo MIME de un audio, codificado en [`IAudio.binary_data`](/slides/python-net/es/aspose.slides/iaudio/binary_data).<br/>            Sólo lectura **str**. |
| [`binary_data`](/slides/python-net/es/aspose.slides/iaudio/binary_data/) | Devuelve una copia de los datos de un audio. En caso de una gran cantidad de datos, considere <br/>            el uso del método [`IAudio.get_stream`](/slides/python-net/es/aspose.slides/iaudio/get_stream) para evitar la carga innecesaria de los datos del audio<br/>            en memoria o incluso una OutOfMemoryException.<br/>            Sólo lectura **int**[]. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/es/aspose.slides/iaudio/get_stream/#) | Devuelve Stream stream para lectura.<br/>            Use 'using' o cierre el stream después de usarlo. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)