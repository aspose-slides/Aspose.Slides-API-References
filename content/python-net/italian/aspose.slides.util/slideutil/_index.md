---
title: SlideUtil class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.util/slideutil/
---
## SlideUtil classe

Offre metodi che aiutano a cercare forme e testo in una presentazione.

Il tipo SlideUtil espone i seguenti membri:

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/it/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Trova la forma mediante testo alternativo in una presentazione PPTX. |
| [`find_shape(slide, alt_text)`](/slides/python-net/it/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Trova la forma mediante testo alternativo su una diapositiva in una presentazione PPTX. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/it/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Modifica la posizione di tutte le forme sulla diapositiva. Allinea le forme ai margini o al bordo della diapositiva<br/>            o le allinea rispetto alle altre. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/it/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Modifica la posizione delle forme selezionate sulla diapositiva. Allinea le forme ai margini o al bordo della diapositiva<br/>            o le allinea rispetto alle altre. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/it/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Modifica la posizione di tutte le forme all'interno del gruppo di forme. Allinea le forme ai margini o al bordo della diapositiva<br/>            o le allinea rispetto alle altre. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/it/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Modifica la posizione delle forme selezionate all'interno del gruppo di forme. Allinea le forme ai margini o al bordo della diapositiva<br/>            o le allinea rispetto alle altre. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/it/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Cerca tutte le forme sulla diapositiva specificata che corrispondono al tipo di segnaposto fornito. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/it/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Trova e sostituisce il testo nella presentazione con il formato fornito |
| [`get_all_text_boxes(slide)`](/slides/python-net/it/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Restituisce tutti i riquadri di testo su una diapositiva in una presentazione PPTX. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/it/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Restituisce tutti i riquadri di testo sulla diapositiva specificata che contengono il testo fornito. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/it/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Restituisce tutti i riquadri di testo in una presentazione PPTX. |
| [`to_save_format(format)`](/slides/python-net/it/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Converte un formato di file sorgente al corrispondente [`SaveFormat`](/slides/python-net/it/aspose.slides.export/saveformat). |

### Vedi anche
* modulo [`aspose.slides.util`](/slides/python-net/it/aspose.slides.util)
* libreria [`Aspose.Slides`](/slides/python-net)