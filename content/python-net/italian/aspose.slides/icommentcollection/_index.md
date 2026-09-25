---
title: ICommentCollection class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/icommentcollection/
---
## ICommentCollection classe

Rappresenta una collezione di commenti di un autore.

Il tipo ICommentCollection espone i seguenti membri:

Restituisce l'elemento all'indice specificato.
            Solo lettura [`IComment`](/slides/python-net/it/aspose.slides/icomment).

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides/icommentcollection/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`to_array(self)`](/slides/python-net/it/aspose.slides/icommentcollection/to_array/#) | Crea e restituisce un array con tutti i commenti. |
| [`to_array(self, start_index, count)`](/slides/python-net/it/aspose.slides/icommentcollection/to_array/#int-int) | Crea e restituisce un array con tutti i commenti dell'intervallo specificato. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/it/aspose.slides/icommentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Aggiunge un nuovo commento alla fine di una collezione. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/it/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Aggiunge un nuovo commento moderno alla fine di una collezione. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/it/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Inserisce un nuovo commento in una collezione all'indice specificato. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/it/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Inserisce un nuovo commento moderno in una collezione all'indice specificato. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides/icommentcollection/remove_at/#int) | Rimuove l'elemento all'indice specificato in una collezione. |
| [`remove(self, comment)`](/slides/python-net/it/aspose.slides/icommentcollection/remove/#icomment) | Rimuove la prima occorrenza del commento specificato in una collezione. |
| [`clear(self)`](/slides/python-net/it/aspose.slides/icommentcollection/clear/#) | Rimuove tutti i commenti da una collezione. |

### Vedi anche
* classe [`IComment`](/slides/python-net/it/aspose.slides/icomment)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)