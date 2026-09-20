---
title: IParagraph class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/iparagraph/
---
## IParagraph classe

Rappresenta un paragrafo di un testo.

Il tipo IParagraph espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`portions`](/slides/python-net/it/aspose.slides/iparagraph/portions/) | Returns the collection of a text portions.<br/>            Read-only [`IPortionCollection`](/slides/python-net/it/aspose.slides/iportioncollection). |
| [`paragraph_format`](/slides/python-net/it/aspose.slides/iparagraph/paragraph_format/) | Returns the formatting object for this paragraph.<br/>            Read-only [`IParagraphFormat`](/slides/python-net/it/aspose.slides/iparagraphformat). |
| [`text`](/slides/python-net/it/aspose.slides/iparagraph/text/) | Ottiene o imposta il testo semplice di un paragrafo.<br/>            Read/write **str**. |
| [`end_paragraph_portion_format`](/slides/python-net/it/aspose.slides/iparagraph/end_paragraph_portion_format/) | Specifica le proprietà della porzione da utilizzare se un'altra porzione viene inserita dopo <br/>            l'ultima. |
| [`slide`](/slides/python-net/it/aspose.slides/iparagraph/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/iparagraph/presentation/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/iparagraph/get_image/#) | Restituisce un'immagine del paragrafo. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/iparagraph/get_image/#float-float) | Restituisce un'immagine del paragrafo con la scala specificata. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/iparagraph/join_portions_with_same_formatting/#) | Unisce le sequenze con la stessa formattazione. |
| [`get_rect(self)`](/slides/python-net/it/aspose.slides/iparagraph/get_rect/#) | Ottiene le coordinate del rettangolo che delimita il paragrafo. Il rettangolo include tutte le righe di<br/>            testo nel paragrafo, incluse quelle vuote. |
| [`get_lines_count(self)`](/slides/python-net/it/aspose.slides/iparagraph/get_lines_count/#) | Ottiene il numero di righe in un paragrafo. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)