---
title: TextFrame class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/textframe/
---
## TextFrame classe

Rappresenta un TextFrame.

Il tipo TextFrame espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`paragraphs`](/slides/python-net/it/aspose.slides/textframe/paragraphs/) | Restituisce l'elenco di tutti i paragrafi in un frame.<br/>            Sola lettura [`IParagraphCollection`](/slides/python-net/it/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/it/aspose.slides/textframe/text/) | Ottiene o imposta il testo semplice per un TextFrame.<br/>            Lettura/scrittura **str**. |
| [`text_frame_format`](/slides/python-net/it/aspose.slides/textframe/text_frame_format/) | Restituisce l'oggetto di formattazione per questo oggetto TextFrame.<br/>            Sola lettura [`ITextFrameFormat`](/slides/python-net/it/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/textframe/hyperlink_queries/) | Fornisce un facile accesso ai collegamenti ipertestuali contenuti.<br/>            Sola lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/it/aspose.slides/textframe/slide/) | Restituisce la diapositiva padre di un TextFrame.<br/>            Sola lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides/textframe/presentation/) | Restituisce la presentazione padre di un TextFrame.<br/>            Sola lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/it/aspose.slides/textframe/parent_shape/) | Restituisce la forma padre o None se l'oggetto padre non implementa l'interfaccia IShape<br/>            Sola lettura [`IShape`](/slides/python-net/it/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/it/aspose.slides/textframe/parent_cell/) | Restituisce la cella padre o None se l'oggetto padre non implementa l'interfaccia ICell.<br/>            Sola lettura [`ICell`](/slides/python-net/it/aspose.slides/icell). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/it/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/it/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/it/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/it/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Evidenzia tutte le occorrenze dell'espressione regolare con il colore specificato. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/it/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Evidenzia tutte le occorrenze dell'espressione regolare con il colore specificato. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/textframe/join_portions_with_same_formatting/#) | Unisce le sequenze con la stessa formattazione in tutti i paragrafi. |
| [`split_text_by_columns(self)`](/slides/python-net/it/aspose.slides/textframe/split_text_by_columns/#) | Divide il contenuto di testo del [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe) in un array di stringhe,<br/>            dove ogni elemento corrisponde a una colonna di testo separata all'interno del frame. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/it/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/it/aspose.slides/textframe/replace_regex/#str-str) | Sostituisce tutte le occorrenze dell'espressione regolare con la stringa specificata. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)