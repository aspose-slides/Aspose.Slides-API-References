---
title: SlideUtil class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.util/slideutil/
---
## SlideUtil klass

Erbjuder metoder som hjälper till att söka efter former och text i en presentation.

SlideUtil-typen exponerar följande medlemmar:

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/sv/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Hitta form efter alternativ text i en PPTX-presentation. |
| [`find_shape(slide, alt_text)`](/slides/python-net/sv/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Hitta form efter alternativ text på en bild i en PPTX-presentation. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/sv/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Ändrar placeringen av alla former på bilden. Justerar former till marginalerna eller bildens kant<br/>            eller justera dem relativt varandra. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/sv/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Ändrar placeringen av valda former på bilden. Justerar former till marginalerna eller bildens kant<br/>            eller justera dem relativt varandra. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/sv/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Ändrar placeringen av alla former inom gruppform. Justerar former till marginalerna eller bildens kant<br/>            eller justera dem relativt varandra. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/sv/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Ändrar placeringen av valda former inom gruppform. Justerar former till marginalerna eller bildens kant<br/>            eller justera dem relativt varandra. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/sv/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Söker efter alla former på den angivna bilden som matchar den givna platshållartyper. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/sv/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Hittar och ersätter text i en presentation med angivet format |
| [`get_all_text_boxes(slide)`](/slides/python-net/sv/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Returnerar alla textramar på en bild i en PPTX-presentation. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/sv/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Returnerar alla textramar på den angivna bilden som innehåller den angivna texten. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/sv/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Returnerar alla textramar i en PPTX-presentation. |
| [`to_save_format(format)`](/slides/python-net/sv/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Konverterar ett källfilformat till motsvarande [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat). |


### Se också
* modul [`aspose.slides.util`](/slides/python-net/sv/aspose.slides.util)
* bibliotek [`Aspose.Slides`](/slides/python-net)