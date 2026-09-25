---
title: CommentCollection class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/commentcollection/
---
## CommentCollection clase

Representa una colección de comentarios de un autor.

El tipo CommentCollection expone los siguientes miembros:

Obtiene el elemento en el índice especificado.  
Solo lectura [`Comment`](/slides/python-net/es/aspose.slides/comment).

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides/commentcollection/__getitem__/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`to_array(self)`](/slides/python-net/es/aspose.slides/commentcollection/to_array/#) | Crea y devuelve una matriz con todos los comentarios. |
| [`to_array(self, start_index, count)`](/slides/python-net/es/aspose.slides/commentcollection/to_array/#int-int) | Crea y devuelve una matriz con todos los comentarios del rango especificado. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/es/aspose.slides/commentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Agrega un nuevo comentario al final de una colección. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/es/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Agrega un nuevo comentario moderno al final de una colección. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/es/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Inserta un nuevo comentario en una colección en el índice especificado. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/es/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Inserta un nuevo comentario moderno en una colección en el índice especificado. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides/commentcollection/remove_at/#int) | Elimina el elemento en el índice especificado de una colección. |
| [`remove(self, comment)`](/slides/python-net/es/aspose.slides/commentcollection/remove/#icomment) | Elimina la primera aparición del comentario especificado en una colección. |
| [`clear(self)`](/slides/python-net/es/aspose.slides/commentcollection/clear/#) | Elimina todos los comentarios de una colección. |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/es/aspose.slides/commentcollection/find_comment_by_idx/#int) | Busca un comentario en la colección por índice. |


### Ver también
* clase [`Comment`](/slides/python-net/es/aspose.slides/comment)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)