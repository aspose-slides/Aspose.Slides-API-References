---
title: ICommentCollection class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/icommentcollection/
---
## ICommentCollection classe

Representa uma coleção de comentários de um autor.

O tipo ICommentCollection expõe os seguintes membros:

Obtém o elemento no índice especificado.
            Somente leitura [`IComment`](/slides/python-net/pt/aspose.slides/icomment).

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides/icommentcollection/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`to_array(self)`](/slides/python-net/pt/aspose.slides/icommentcollection/to_array/#) | Cria e retorna um array com todos os comentários. |
| [`to_array(self, start_index, count)`](/slides/python-net/pt/aspose.slides/icommentcollection/to_array/#int-int) | Cria e retorna um array com todos os comentários do intervalo especificado. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/pt/aspose.slides/icommentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | adiciona um novo comentário ao final da coleção. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/pt/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | adiciona um novo comentário moderno ao final da coleção. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/pt/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | insere um novo comentário na coleção no índice especificado. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/pt/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | insere um novo comentário moderno na coleção no índice especificado. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides/icommentcollection/remove_at/#int) | remove o elemento no índice especificado em uma coleção. |
| [`remove(self, comment)`](/slides/python-net/pt/aspose.slides/icommentcollection/remove/#icomment) | remove a primeira ocorrência do comentário especificado em uma coleção. |
| [`clear(self)`](/slides/python-net/pt/aspose.slides/icommentcollection/clear/#) | remove todos os comentários de uma coleção. |


### Ver também
* classe [`IComment`](/slides/python-net/pt/aspose.slides/icomment)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)