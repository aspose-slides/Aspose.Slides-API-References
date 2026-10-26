---
title: SlideCollection class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/slidecollection/
---
## SlideCollection clase

Representa una colección de diapositivas.

El tipo SlideCollection expone los siguientes miembros:

Obtiene el elemento en el índice especificado.  
Solo lectura [`Slide`](/slides/python-net/es/aspose.slides/slide).

## Indexer

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides/slidecollection/__getitem__/) |  |

## Methods

| Método | Descripción |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/es/aspose.slides/slidecollection/add_clone/#islide) | Agrega una copia de una diapositiva especificada al final de la colección. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/es/aspose.slides/slidecollection/add_clone/#islide-isection) | Agrega una copia de una diapositiva especificada al final de la sección especificada. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/es/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Agrega una copia de una diapositiva especificada al final de la colección. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/es/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Agrega una copia de una diapositiva fuente especificada al final de la colección.<br/>            Se seleccionará automáticamente la distribución apropiada del maestro especificado <br/>            (la distribución apropiada es la que tiene el mismo Tipo o Nombre que <br/>            la distribución de la diapositiva fuente). Si no hay una distribución apropiada entonces<br/>            la distribución de la diapositiva fuente será clonada (si allowCloneMissingLayout <br/>            es true) o se lanzará PptxEditException (si allowCloneMissingLayout <br/>            es false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/es/aspose.slides/slidecollection/insert_clone/#int-islide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/es/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/es/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Inserta una copia de una diapositiva fuente especificada en la posición especificada de la colección.<br/>            Se seleccionará automáticamente la distribución apropiada del maestro especificado <br/>            (la distribución apropiada es la que tiene el mismo Tipo o Nombre que <br/>            la distribución de la diapositiva fuente). Si no hay una distribución apropiada entonces<br/>            la distribución de la diapositiva fuente será clonada (si allowCloneMissingLayout <br/>            es true) o se lanzará PptxEditException (si allowCloneMissingLayout <br/>            es false). |
| [`to_array(self)`](/slides/python-net/es/aspose.slides/slidecollection/to_array/#) | Crea y devuelve una matriz con todas las diapositivas. |
| [`to_array(self, start_index, count)`](/slides/python-net/es/aspose.slides/slidecollection/to_array/#int-int) | Crea y devuelve una matriz con todas las diapositivas del rango especificado.<br/>            Un índice de la primera diapositiva a agregar. Un número de diapositivas a agregar. |
| [`reorder(self, index, slide)`](/slides/python-net/es/aspose.slides/slidecollection/reorder/#int-islide) | Mueve la diapositiva de la colección a la posición especificada. |
| [`reorder(self, index, slides)`](/slides/python-net/es/aspose.slides/slidecollection/reorder/#int-listislide) | Mueve diapositivas de la colección a la posición especificada.<br/>            Las diapositivas se colocarán comenzando desde el índice en el orden en que aparecen en la lista. |
| [`add_from_pdf(self, path)`](/slides/python-net/es/aspose.slides/slidecollection/add_from_pdf/#str) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/es/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección considerando las opciones de importación PDF. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/es/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/es/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/es/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [`add_from_html(self, html_text)`](/slides/python-net/es/aspose.slides/slidecollection/add_from_html/#str) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/es/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [`add_from_html(self, html_stream)`](/slides/python-net/es/aspose.slides/slidecollection/add_from_html/#iorawiobase) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/es/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/es/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/es/aspose.slides/slidecollection/insert_from_html/#int-str) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/es/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/es/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/es/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/es/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/es/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [`add_empty_slide(self, layout)`](/slides/python-net/es/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Agrega una nueva diapositiva vacía al final de la colección. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/es/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [`remove(self, value)`](/slides/python-net/es/aspose.slides/slidecollection/remove/#islide) | Elimina la primera ocurrencia de un objeto específico de la colección. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides/slidecollection/remove_at/#int) | Elimina el elemento en el índice especificado de la colección. |
| [`index_of(self, slide)`](/slides/python-net/es/aspose.slides/slidecollection/index_of/#islide) | Devuelve el índice de la diapositiva especificada en la colección. |


### Ver también
* clase [`Slide`](/slides/python-net/es/aspose.slides/slide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)