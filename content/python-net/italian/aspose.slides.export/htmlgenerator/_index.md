---
title: HtmlGenerator class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator classe

Generatore Html.

Il tipo HtmlGenerator espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`slide_image_size`](/slides/python-net/it/aspose.slides.export/htmlgenerator/slide_image_size/) | Restituisce la dimensione dell'immagine della diapositiva.<br/>            Solo lettura **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/it/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Restituisce l'unità in cui è specificata la dimensione dell'immagine della diapositiva.<br/>            Solo lettura [`SvgCoordinateUnit`](/slides/python-net/it/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/it/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Restituisce il codice CSS dell'unità in cui è specificata la dimensione dell'immagine della diapositiva.<br/>            Solo lettura **str**. |
| [`previous_slide_index`](/slides/python-net/it/aspose.slides.export/htmlgenerator/previous_slide_index/) | Restituisce l'indice della diapositiva renderizzata precedentemente o -1 se la prima diapositiva è in fase di rendering.<br/>            Solo lettura **int**. |
| [`slide_index`](/slides/python-net/it/aspose.slides.export/htmlgenerator/slide_index/) | Restituisce l'indice della diapositiva attualmente in fase di rendering.<br/>            Solo lettura **int**. |
| [`next_slide_index`](/slides/python-net/it/aspose.slides.export/htmlgenerator/next_slide_index/) | Restituisce l'indice di una diapositiva che verrà renderizzata dopo la diapositiva corrente o -1 se si sta renderizzando l'ultima diapositiva.<br/>            Solo lettura **int**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/it/aspose.slides.export/htmlgenerator/add_html/#str) | Aggiunge testo HTML formattato. |
| [`add_html(self, html)`](/slides/python-net/it/aspose.slides.export/htmlgenerator/add_html/#listchar) | Aggiunge testo HTML formattato. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/it/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Aggiunge testo HTML formattato. |
| [`add_text(self, text)`](/slides/python-net/it/aspose.slides.export/htmlgenerator/add_text/#str) | Aggiunge testo semplice ai file html, sostituendo i caratteri speciali con entità html.<br/>            Interruzioni di riga e spazi bianchi non vengono sostituiti. |
| [`add_text(self, text)`](/slides/python-net/it/aspose.slides.export/htmlgenerator/add_text/#listchar) | Aggiunge testo semplice ai file html, sostituendo i caratteri speciali con entità html.<br/>            Interruzioni di riga e spazi bianchi non vengono sostituiti. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/it/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | Aggiunge testo semplice ai file html, sostituendo i caratteri speciali con entità html.<br/>            Interruzioni di riga e spazi bianchi non vengono sostituiti. |
| [`add_attribute_value(self, value)`](/slides/python-net/it/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Escapa il valore dell'attributo e lo aggiunge al file html. |
| [`add_attribute_value(self, value)`](/slides/python-net/it/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Escapa il valore dell'attributo e lo aggiunge al file html. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/it/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Escapa il valore dell'attributo e lo aggiunge al file html. |

### Vedi anche
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)