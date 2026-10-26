---
title: SlideUtil class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.util/slideutil/
---
## SlideUtil třída

Nabízí metody, které pomáhají vyhledávat tvary a text v prezentaci.

Typ SlideUtil zveřejňuje následující členy:

## Metody

| Metoda | Popis |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/cs/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Najde tvar podle alternativního textu v prezentaci PPTX. |
| [`find_shape(slide, alt_text)`](/slides/python-net/cs/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Najde tvar podle alternativního textu na snímku v prezentaci PPTX. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/cs/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Mění umístění všech tvarů na snímku. Zarovnává tvary k okrajům nebo k okraji snímku<br/>            nebo je zarovnává relativně vůči sobě navzájem. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/cs/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Mění umístění vybraných tvarů na snímku. Zarovnává tvary k okrajům nebo k okraji snímku<br/>            nebo je zarovnává relativně vůči sobě navzájem. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/cs/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Mění umístění všech tvarů ve skupinovém tvaru. Zarovnává tvary k okrajům nebo k okraji snímku<br/>            nebo je zarovnává relativně vůči sobě navzájem. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/cs/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Mění umístění vybraných tvarů ve skupinovém tvaru. Zarovnává tvary k okrajům nebo k okraji snímku<br/>            nebo je zarovnává relativně vůči sobě navzájem. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/cs/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Vyhledá všechny tvary na určeném snímku, které odpovídají danému typu zástupného textu. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/cs/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Najde a nahradí text v prezentaci daným formátem |
| [`get_all_text_boxes(slide)`](/slides/python-net/cs/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Vrátí všechny textové rámečky na snímku v prezentaci PPTX. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/cs/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Vrátí všechny textové rámečky na určeném snímku, které obsahují daný text. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/cs/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Vrátí všechny textové rámečky v prezentaci PPTX. |
| [`to_save_format(format)`](/slides/python-net/cs/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Převede formát zdrojového souboru na odpovídající [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat). |

### Viz také
* modul [`aspose.slides.util`](/slides/python-net/cs/aspose.slides.util)
* knihovna [`Aspose.Slides`](/slides/python-net)