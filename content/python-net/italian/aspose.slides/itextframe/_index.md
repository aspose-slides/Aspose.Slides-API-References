---
title: ITextFrame class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/itextframe/
---
## ITextFrame classe

Rappresenta un TextFrame.

Il tipo ITextFrame espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`paragraphs`](/slides/python-net/it/aspose.slides/itextframe/paragraphs/) | Restituisce l'elenco di tutti i paragrafi in un frame.<br/>            Solo lettura [`IParagraphCollection`](/slides/python-net/it/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/it/aspose.slides/itextframe/text/) | Ottiene o imposta il testo semplice per un TextFrame.<br/>            Lettura/scrittura **str**. |
| [`text_frame_format`](/slides/python-net/it/aspose.slides/itextframe/text_frame_format/) | Restituisce l'oggetto di formattazione per questo oggetto TextFrame.<br/>            Solo lettura [`ITextFrameFormat`](/slides/python-net/it/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/itextframe/hyperlink_queries/) | Fornisce un accesso facile ai collegamenti ipertestuali contenuti.<br/>            Solo lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/it/aspose.slides/itextframe/parent_shape/) | Restituisce la forma padre o None se l'oggetto padre non implementa l'interfaccia IShape<br/>            Solo lettura [`IShape`](/slides/python-net/it/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/it/aspose.slides/itextframe/parent_cell/) | Restituisce la cella padre o None se l'oggetto padre non implementa l'interfaccia ICell.<br/>            Solo lettura [`ICell`](/slides/python-net/it/aspose.slides/icell). |
| [`slide`](/slides/python-net/it/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/itextframe/presentation/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/it/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/it/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/it/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/it/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Evidenzia tutte le occorrenze dell'espressione regolare con il colore specificato. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/it/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Evidenzia tutte le occorrenze dell'espressione regolare con il colore specificato. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Unisce le sequenze con la stessa formattazione in tutti i paragrafi. |
| [`split_text_by_columns(self)`](/slides/python-net/it/aspose.slides/itextframe/split_text_by_columns/#) | Divide il contenuto testuale del [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe) in un array di stringhe,<br/>            dove ogni elemento corrisponde a una colonna di testo separata all'interno del frame. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/it/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/it/aspose.slides/itextframe/replace_regex/#str-str) | Sostituisce tutte le occorrenze dell'espressione regolare con la stringa specificata. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)