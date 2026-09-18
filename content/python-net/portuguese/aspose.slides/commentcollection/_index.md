---
title: CommentCollection class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/commentcollection/
---
## CommentCollection classe

Representa uma coleção de comentários de um autor.

O tipo CommentCollection expõe os seguintes membros:

Obtém o elemento no índice especificado. Somente leitura [`Comment`](/slides/python-net/pt/aspose.slides/comment).

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides/commentcollection/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`to_array(self)`](/slides/python-net/pt/aspose.slides/commentcollection/to_array/#) | Cria e retorna um array com todos os comentários. |
| [`to_array(self, start_index, count)`](/slides/python-net/pt/aspose.slides/commentcollection/to_array/#int-int) | Cria e retorna um array com todos os comentários do intervalo especificado. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/pt/aspose.slides/commentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | Adiciona um novo comentário ao final de uma coleção. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/pt/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | Adiciona um novo comentário moderno ao final de uma coleção. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/pt/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | Insere um novo comentário em uma coleção no índice especificado. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/pt/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | Insere um novo comentário moderno em uma coleção no índice especificado. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides/commentcollection/remove_at/#int) | Remove o elemento no índice especificado em uma coleção. |
| [`remove(self, comment)`](/slides/python-net/pt/aspose.slides/commentcollection/remove/#icomment) | Remove a primeira ocorrência do comentário especificado em uma coleção. |
| [`clear(self)`](/slides/python-net/pt/aspose.slides/commentcollection/clear/#) | Remove todos os comentários de uma coleção. |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/pt/aspose.slides/commentcollection/find_comment_by_idx/#int) | Encontra um comentário na coleção por índice. |


### Veja Também
* classe [`Comment`](/slides/python-net/pt/aspose.slides/comment)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)