---
title: SlideUtil class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.util/slideutil/
---
## SlideUtil clase

Ofrece métodos que ayudan a buscar formas y texto en una presentación.

El tipo SlideUtil expone los siguientes miembros:

## Métodos

| Método | Descripción |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/es/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Buscar forma por texto alternativo en una presentación PPTX. |
| [`find_shape(slide, alt_text)`](/slides/python-net/es/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Buscar forma por texto alternativo en una diapositiva de una presentación PPTX. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/es/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Cambia la ubicación de todas las formas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva<br/>            o las alinea entre sí. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/es/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Cambia la ubicación de las formas seleccionadas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva<br/>             o las alinea entre sí. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/es/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Cambia la ubicación de todas las formas dentro del grupo de formas. Alinea las formas a los márgenes o al borde de la diapositiva<br/>            o las alinea entre sí. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/es/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Cambia la ubicación de las formas seleccionadas dentro del grupo de formas. Alinea las formas a los márgenes o al borde de la diapositiva<br/>            o las alinea entre sí. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/es/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Busca todas las formas en la diapositiva especificada que coincidan con el tipo de marcador de posición dado. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/es/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Busca y reemplaza texto en la presentación con el formato dado |
| [`get_all_text_boxes(slide)`](/slides/python-net/es/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Devuelve todos los marcos de texto en una diapositiva de una presentación PPTX. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/es/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Devuelve todos los marcos de texto en la diapositiva especificada que contienen el texto dado. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/es/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Devuelve todos los marcos de texto en una presentación PPTX. |
| [`to_save_format(format)`](/slides/python-net/es/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Convierte un formato de archivo fuente al [`SaveFormat`](/slides/python-net/es/aspose.slides.export/saveformat) correspondiente. |

### Ver también
* módulo [`aspose.slides.util`](/slides/python-net/es/aspose.slides.util)
* biblioteca [`Aspose.Slides`](/slides/python-net)