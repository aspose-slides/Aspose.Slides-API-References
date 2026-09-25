---
title: IHtmlGenerator class
second_title: Aspose.Slides para Python a través de la referencia de la API .NET
description: 
type: docs
url: /es/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator clase

Generador HTML.

El tipo IHtmlGenerator expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`slide_image_size`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Devuelve el tamaño de la imagen de la diapositiva.<br/>            Solo lectura [`SizeF`](/slides/python-net/es/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Devuelve la unidad en la que se especifica el tamaño de la imagen de la diapositiva.<br/>            Solo lectura [`SvgCoordinateUnit`](/slides/python-net/es/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Devuelve un código css de la unidad en la que se especifica el tamaño de la imagen de la diapositiva.<br/>            Solo lectura **str**. |
| [`previous_slide_index`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Devuelve el índice de la diapositiva renderizada previamente o -1 si se está renderizando la primera diapositiva.<br/>            Solo lectura **int**. |
| [`slide_index`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/slide_index/) | Devuelve el índice de la diapositiva que se está renderizando actualmente.<br/>            Solo lectura **int**. |
| [`next_slide_index`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Devuelve el índice de una diapositiva que se renderizará después de la diapositiva actual o -1 si se está renderizando la última diapositiva.<br/>            Solo lectura **int**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/add_html/#str) | Agrega texto HTML formateado. |
| [`add_html(self, html)`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Agrega texto HTML formateado. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Agrega texto HTML formateado. |
| [`add_text(self, text)`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/add_text/#str) | Agrega texto sin formato a los archivos html, reemplazando caracteres especiales con entidades html.<br/>            Los saltos de línea y los espacios en blanco no se reemplazan. |
| [`add_text(self, text)`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Agrega texto sin formato a los archivos html, reemplazando caracteres especiales con entidades html.<br/>            Los saltos de línea y los espacios en blanco no se reemplazan. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Agrega texto sin formato a los archivos html, reemplazando caracteres especiales con entidades html.<br/>            Los saltos de línea y los espacios en blanco no se reemplazan. |
| [`add_attribute_value(self, value)`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Escapa el valor del atributo y lo agrega al archivo html. |
| [`add_attribute_value(self, value)`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Escapa el valor del atributo y lo agrega al archivo html. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/es/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Escapa el valor del atributo y lo agrega al archivo html. |

### Ver también
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)