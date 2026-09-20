---
title: IHtmlFormattingController class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController classe

Controlla la generazione di un file html.

Il tipo IHtmlFormattingController espone i seguenti membri:

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/it/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Chiamata per scrivere l'intestazione del documento html. Chiamata una volta per conversione della presentazione. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/it/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Chiamata per scrivere il piè di pagina del documento html. Chiamata una volta per conversione della presentazione. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/it/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Chiamata per scrivere l'intestazione della diapositiva html. Chiamata una volta per ciascuna diapositiva. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/it/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Chiamata per scrivere il piè di pagina della diapositiva html. Chiamata una volta per ciascuna diapositiva. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/it/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Chiamata prima del rendering della forma. Chiamata una volta per ciascuna forma. Se questa funzione scrive qualcosa nel generatore, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento html aggiunto sarà inserito e una nuova immagine sarà avviata sopra la precedente. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/it/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Chiamata prima del rendering della forma. Chiamata una volta per ciascuna forma. Se questa funzione scrive qualcosa nel generatore, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento html aggiunto sarà inserito e una nuova immagine sarà avviata sopra la precedente. |

### Vedi anche
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)