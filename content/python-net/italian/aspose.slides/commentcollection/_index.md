---
title: CommentCollection class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/commentcollection/
---
## CommentCollection classe

Rappresenta una raccolta di commenti di un singolo autore.

Il tipo CommentCollection espone i seguenti membri:

Restituisce l'elemento all'indice specificato.  
            Solo lettura [`Comment`](/slides/python-net/it/aspose.slides/comment).

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides/commentcollection/__getitem__/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`to_array(self)`](/slides/python-net/it/aspose.slides/commentcollection/to_array/#) | Crea e restituisce un array con tutti i commenti. |
| [`to_array(self, start_index, count)`](/slides/python-net/it/aspose.slides/commentcollection/to_array/#int-int) | Crea e restituisce un array con tutti i commenti dell'intervallo specificato. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/it/aspose.slides/commentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | Aggiunge un nuovo commento alla fine della raccolta. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/it/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | Aggiunge un nuovo commento moderno alla fine della raccolta. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/it/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | Inserisce un nuovo commento nella raccolta all'indice specificato. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/it/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | Inserisce un nuovo commento moderno nella raccolta all'indice specificato. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides/commentcollection/remove_at/#int) | Rimuove l'elemento all'indice specificato nella raccolta. |
| [`remove(self, comment)`](/slides/python-net/it/aspose.slides/commentcollection/remove/#icomment) | Rimuove la prima occorrenza del commento specificato nella raccolta. |
| [`clear(self)`](/slides/python-net/it/aspose.slides/commentcollection/clear/#) | Rimuove tutti i commenti dalla raccolta. |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/it/aspose.slides/commentcollection/find_comment_by_idx/#int) | Trova un commento nella raccolta per indice. |


### Vedi anche
* classe [`Comment`](/slides/python-net/it/aspose.slides/comment)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)