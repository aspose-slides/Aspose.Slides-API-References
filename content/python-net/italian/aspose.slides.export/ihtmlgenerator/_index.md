---
title: IHtmlGenerator class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator classe

Html generator.

The IHtmlGenerator type exposes the following members:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`slide_image_size`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Restituisce la dimensione dell'immagine della diapositiva.<br/>            Solo lettura **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Restituisce l'unità in cui è specificata la dimensione dell'immagine della diapositiva.<br/>            Solo lettura [`SvgCoordinateUnit`](/slides/python-net/it/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Restituisce un codice CSS dell'unità in cui è specificata la dimensione dell'immagine della diapositiva.<br/>            Solo lettura **str**. |
| [`previous_slide_index`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Restituisce l'indice della diapositiva precedentemente renderizzata o -1 se la prima diapositiva è in fase di rendering.<br/>            Solo lettura **int**. |
| [`slide_index`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/slide_index/) | Restituisce l'indice della diapositiva attualmente in fase di rendering.<br/>            Solo lettura **int**. |
| [`next_slide_index`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Restituisce l'indice di una diapositiva che verrà renderizzata dopo la diapositiva corrente o -1 se si sta renderizzando l'ultima diapositiva.<br/>            Solo lettura **int**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/add_html/#str) | Aggiunge testo HTML formattato. |
| [`add_html(self, html)`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Aggiunge testo HTML formattato. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Aggiunge testo HTML formattato. |
| [`add_text(self, text)`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/add_text/#str) | Aggiunge testo semplice ai file HTML, sostituendo i caratteri speciali con entità HTML.<br/>            I ritorni a capo e gli spazi bianchi non vengono sostituiti. |
| [`add_text(self, text)`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Aggiunge testo semplice ai file HTML, sostituendo i caratteri speciali con entità HTML.<br/>            I ritorni a capo e gli spazi bianchi non vengono sostituiti. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Aggiunge testo semplice ai file HTML, sostituendo i caratteri speciali con entità HTML.<br/>            I ritorni a capo e gli spazi bianchi non vengono sostituiti. |
| [`add_attribute_value(self, value)`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Inserisce virgolette al valore dell'attributo e lo aggiunge al file HTML. |
| [`add_attribute_value(self, value)`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Inserisce virgolette al valore dell'attributo e lo aggiunge al file HTML. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Inserisce virgolette al valore dell'attributo e lo aggiunge al file HTML. |


### Vedi anche
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)