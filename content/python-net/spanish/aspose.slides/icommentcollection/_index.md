---
title: ICommentCollection class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/icommentcollection/
---
## ICommentCollection clase

Representa una colección de comentarios de un autor.

El tipo ICommentCollection expone los siguientes miembros:

Obtiene el elemento en el índice especificado.
            Solo lectura [`IComment`](/slides/python-net/es/aspose.slides/icomment).

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides/icommentcollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`to_array(self)`](/slides/python-net/es/aspose.slides/icommentcollection/to_array/#) | Crea y devuelve una matriz con todos los comentarios. |
| [`to_array(self, start_index, count)`](/slides/python-net/es/aspose.slides/icommentcollection/to_array/#int-int) | Crea y devuelve una matriz con todos los comentarios del rango especificado. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/es/aspose.slides/icommentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Añade un nuevo comentario al final de una colección. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/es/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Añade un nuevo comentario moderno al final de una colección. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/es/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Inserta un nuevo comentario en una colección en el índice especificado. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/es/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Inserta un nuevo comentario moderno en una colección en el índice especificado. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides/icommentcollection/remove_at/#int) | Elimina el elemento en el índice especificado de una colección. |
| [`remove(self, comment)`](/slides/python-net/es/aspose.slides/icommentcollection/remove/#icomment) | Elimina la primera ocurrencia del comentario especificado en una colección. |
| [`clear(self)`](/slides/python-net/es/aspose.slides/icommentcollection/clear/#) | Elimina todos los comentarios de una colección. |


### Ver también
* clase [`IComment`](/slides/python-net/es/aspose.slides/icomment)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)