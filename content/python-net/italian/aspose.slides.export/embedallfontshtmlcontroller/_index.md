---
title: EmbedAllFontsHtmlController class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController classe

La classe del controller di formattazione da usare per incorporare tutti i caratteri della presentazione in formato WOFF.

Il tipo EmbedAllFontsHtmlController espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Crea una nuova istanza |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Crea una nuova istanza |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Chiamato per scrivere l'intestazione del documento html. Chiamato una volta per conversione della presentazione. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Chiamato per scrivere il piè di pagina del documento html. Chiamato una volta per conversione della presentazione. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Chiamato per scrivere l'intestazione della diapositiva html. Chiamato una volta per ciascuna diapositiva. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Chiamato per scrivere il piè di pagina della diapositiva html. Chiamato una volta per ciascuna diapositiva. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Chiamato prima del rendering della forma. Chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa al generatore, la generazione dell'immagine della diapositiva corrente verrà terminata, il frammento html aggiunto verrà inserito e una nuova immagine sarà avviata sopra la precedente. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Chiamato prima del rendering della forma. Chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa al generatore, la generazione dell'immagine della diapositiva corrente verrà terminata, il frammento html aggiunto verrà inserito e una nuova immagine sarà avviata sopra la precedente. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Scrivi tutti i caratteri contenuti in [`Presentation`](/slides/python-net/it/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Scrive i dati come base64 direttamente nel documento HTML. |

### Vedi anche
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)