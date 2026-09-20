---
title: SlideCollection class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/slidecollection/
---
## SlideCollection classe

Rappresenta una raccolta di diapositive.

Il tipo SlideCollection espone i seguenti membri:

Restituisce l'elemento all'indice specificato.
            Solo lettura [`Slide`](/slides/python-net/it/aspose.slides/slide).

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides/slidecollection/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/it/aspose.slides/slidecollection/add_clone/#islide) | Aggiunge una copia di una diapositiva specificata alla fine della raccolta. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/it/aspose.slides/slidecollection/add_clone/#islide-isection) | Aggiunge una copia di una diapositiva specificata alla fine della sezione specificata. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/it/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Aggiunge una copia di una diapositiva specificata alla fine della raccolta. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/it/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Aggiunge una copia di una diapositiva di origine specificata alla fine della raccolta.<br/>            Il layout appropriato verrà selezionato automaticamente dal master specificato <br/>            (il layout appropriato è il layout con lo stesso Tipo o Nome del <br/>            layout della diapositiva di origine). Se non esiste un layout appropriato, <br/>            il layout della diapositiva di origine verrà clonato (se allowCloneMissingLayout <br/>            è true) oppure verrà sollevata un'eccezione PptxEditException (se allowCloneMissingLayout <br/>            è false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/it/aspose.slides/slidecollection/insert_clone/#int-islide) | Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/it/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/it/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Inserisce una copia di una diapositiva di origine specificata nella posizione specificata della raccolta.<br/>            Il layout appropriato verrà selezionato automaticamente dal master specificato <br/>            (il layout appropriato è il layout con lo stesso Tipo o Nome del <br/>            layout della diapositiva di origine). Se non esiste un layout appropriato, <br/>            il layout della diapositiva di origine verrà clonato (se allowCloneMissingLayout <br/>            è true) oppure verrà sollevata un'eccezione PptxEditException (se allowCloneMissingLayout <br/>            è false). |
| [`to_array(self)`](/slides/python-net/it/aspose.slides/slidecollection/to_array/#) | Crea e restituisce un array contenente tutte le diapositive. |
| [`to_array(self, start_index, count)`](/slides/python-net/it/aspose.slides/slidecollection/to_array/#int-int) | Crea e restituisce un array contenente tutte le diapositive dell'intervallo specificato.<br/>            Un indice della prima diapositiva da aggiungere. Un numero di diapositive da aggiungere. |
| [`reorder(self, index, slide)`](/slides/python-net/it/aspose.slides/slidecollection/reorder/#int-islide) | Sposta una diapositiva dalla raccolta alla posizione specificata. |
| [`reorder(self, index, slides)`](/slides/python-net/it/aspose.slides/slidecollection/reorder/#int-listislide) | Sposta le diapositive dalla raccolta alla posizione specificata.<br/>            Le diapositive saranno posizionate a partire dall'indice nell'ordine in cui appaiono nella lista. |
| [`add_from_pdf(self, path)`](/slides/python-net/it/aspose.slides/slidecollection/add_from_pdf/#str) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/it/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta tenendo conto delle opzioni di importazione PDF. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/it/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/it/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/it/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Crea diapositive da testo HTML e le aggiunge alla fine della raccolta. |
| [`add_from_html(self, html_text)`](/slides/python-net/it/aspose.slides/slidecollection/add_from_html/#str) | Crea diapositive da testo HTML e le aggiunge alla fine della raccolta. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/it/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Crea diapositive da testo HTML e le aggiunge alla fine della raccolta. |
| [`add_from_html(self, html_stream)`](/slides/python-net/it/aspose.slides/slidecollection/add_from_html/#iorawiobase) | Crea diapositive da testo HTML e le aggiunge alla fine della raccolta. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/it/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/it/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/it/aspose.slides/slidecollection/insert_from_html/#int-str) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/it/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/it/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/it/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/it/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/it/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [`add_empty_slide(self, layout)`](/slides/python-net/it/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Aggiunge una nuova diapositiva vuota alla fine della raccolta. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/it/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta. |
| [`remove(self, value)`](/slides/python-net/it/aspose.slides/slidecollection/remove/#islide) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides/slidecollection/remove_at/#int) | Rimuove l'elemento all'indice specificato della raccolta. |
| [`index_of(self, slide)`](/slides/python-net/it/aspose.slides/slidecollection/index_of/#islide) | Restituisce l'indice della diapositiva specificata nella raccolta. |


### Vedi anche
* classe [`Slide`](/slides/python-net/it/aspose.slides/slide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)