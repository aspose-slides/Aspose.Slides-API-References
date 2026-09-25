---
title: CommentCollection class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/commentcollection/
---
## CommentCollection classe

Rappresenta una raccolta di commenti di un autore.

Il tipo CommentCollection espone i seguenti membri:

Ottiene l'elemento all'indice specificato.
            Sola lettura [`Comment`](/slides/python-net/it/aspose.slides/comment).

## Indicizzatore

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides/commentcollection/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`to_array(self)`](/slides/python-net/it/aspose.slides/commentcollection/to_array/#) | Crea e restituisce un array con tutti i commenti. |
| [`to_array(self, start_index, count)`](/slides/python-net/it/aspose.slides/commentcollection/to_array/#int-int) | Crea e restituisce un array con tutti i commenti dell'intervallo specificato. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/it/aspose.slides/commentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Aggiunge un nuovo commento alla fine di una raccolta. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/it/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Aggiunge un nuovo commento moderno alla fine di una raccolta. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/it/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Inserisce un nuovo commento in una raccolta all'indice specificato. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/it/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Inserisce un nuovo commento moderno in una raccolta all'indice specificato. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides/commentcollection/remove_at/#int) | Rimuove l'elemento all'indice specificato in una raccolta. |
| [`remove(self, comment)`](/slides/python-net/it/aspose.slides/commentcollection/remove/#icomment) | Rimuove la prima occorrenza del commento specificato in una raccolta. |
| [`clear(self)`](/slides/python-net/it/aspose.slides/commentcollection/clear/#) | Rimuove tutti i commenti da una raccolta. |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/it/aspose.slides/commentcollection/find_comment_by_idx/#int) | Trova un commento nella raccolta per indice. |


### Vedi anche
* classe [`Comment`](/slides/python-net/it/aspose.slides/comment)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)