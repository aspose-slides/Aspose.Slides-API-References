---
title: HtmlGenerator class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/htmlgenerator/
---
## Clase HtmlGenerator

Generador HTML.

El tipo HtmlGenerator expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/es/aspose.slides.export/htmlgenerator/slide_image_size/) | Devuelve el tamaño de la imagen de la diapositiva.<br/>            Solo lectura [`SizeF`](/slides/python-net/es/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/es/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Devuelve una unidad en la que se especifica el tamaño de la imagen de la diapositiva.<br/>            Solo lectura [`SvgCoordinateUnit`](/slides/python-net/es/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/es/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Devuelve un código css de la unidad en la que se especifica el tamaño de la imagen de la diapositiva.<br/>            Solo lectura **str**. |
| [`previous_slide_index`](/slides/python-net/es/aspose.slides.export/htmlgenerator/previous_slide_index/) | Devuelve el índice de la diapositiva previamente renderizada o -1 si es la primera diapositiva que se está renderizando.<br/>            Solo lectura **int**. |
| [`slide_index`](/slides/python-net/es/aspose.slides.export/htmlgenerator/slide_index/) | Devuelve el índice de la diapositiva que se está renderizando en este momento.<br/>            Solo lectura **int**. |
| [`next_slide_index`](/slides/python-net/es/aspose.slides.export/htmlgenerator/next_slide_index/) | Devuelve el índice de una diapositiva que se renderizará después de la diapositiva actual o -1 si actualmente se está renderizando la última diapositiva.<br/>            Solo lectura **int**. |

## Métodos

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_html/#str) | Agrega texto HTML formateado. |
| [`add_html(self, html)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_html/#listchar) | Agrega texto HTML formateado. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Agrega texto HTML formateado. |
| [`add_text(self, text)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_text/#str) | Agrega texto plano a los archivos html, reemplazando caracteres especiales con entidades html.<br/>            Los saltos de línea y los espacios en blanco no se reemplazan. |
| [`add_text(self, text)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_text/#listchar) | Agrega texto plano a los archivos html, reemplazando caracteres especiales con entidades html.<br/>            Los saltos de línea y los espacios en blanco no se reemplazan. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | Agrega texto plano a los archivos html, reemplazando caracteres especiales con entidades html.<br/>            Los saltos de línea y los espacios en blanco no se reemplazan. |
| [`add_attribute_value(self, value)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Cita el valor del atributo y lo agrega al archivo html. |
| [`add_attribute_value(self, value)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Cita el valor del atributo y lo agrega al archivo html. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Cita el valor del atributo y lo agrega al archivo html. |

### Ver también
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)