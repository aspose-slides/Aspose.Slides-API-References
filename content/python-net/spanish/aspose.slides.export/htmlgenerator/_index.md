---
title: HtmlGenerator class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
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
| [`slide_image_size`](/slides/python-net/es/aspose.slides.export/htmlgenerator/slide_image_size/) | Returns slide image size.<br/>            Solo lectura **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/es/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Returns a unit in which slide image size is specified.<br/>            Solo lectura [`SvgCoordinateUnit`](/slides/python-net/es/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/es/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Returns a css code of unit in which slide image size is specified.<br/>            Solo lectura **str**. |
| [`previous_slide_index`](/slides/python-net/es/aspose.slides.export/htmlgenerator/previous_slide_index/) | Returns index of previously rendered slide or -1 if first slide is rendering.<br/>            Solo lectura **int**. |
| [`slide_index`](/slides/python-net/es/aspose.slides.export/htmlgenerator/slide_index/) | Returns index of currently rendering slide.<br/>            Solo lectura **int**. |
| [`next_slide_index`](/slides/python-net/es/aspose.slides.export/htmlgenerator/next_slide_index/) | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide.<br/>            Solo lectura **int**. |

## Métodos

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_html/#str) | Añade texto HTML formateado. |
| [`add_html(self, html)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_html/#listchar) | Añade texto HTML formateado. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Añade texto HTML formateado. |
| [`add_text(self, text)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_text/#str) | Añade texto sin formato a los archivos html, reemplazando caracteres especiales con entidades html.<br/>            Los saltos de línea y espacios en blanco no se reemplazan. |
| [`add_text(self, text)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_text/#listchar) | Añade texto sin formato a los archivos html, reemplazando caracteres especiales con entidades html.<br/>            Los saltos de línea y espacios en blanco no se reemplazan. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | Añade texto sin formato a los archivos html, reemplazando caracteres especiales con entidades html.<br/>            Los saltos de línea y espacios en blanco no se reemplazan. |
| [`add_attribute_value(self, value)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Cita el valor del atributo y lo agrega al archivo html. |
| [`add_attribute_value(self, value)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Cita el valor del atributo y lo agrega al archivo html. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/es/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Cita el valor del atributo y lo agrega al archivo html. |

### Ver también
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)