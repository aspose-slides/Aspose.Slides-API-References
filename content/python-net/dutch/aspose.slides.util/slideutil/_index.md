---
title: SlideUtil class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.util/slideutil/
---
## SlideUtil class

Biedt methoden die helpen bij het zoeken naar vormen en tekst in een presentatie.

Het SlideUtil-type geeft de volgende leden weer:

## Methoden

| Method | Description |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/nl/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Zoek een vorm op basis van alternatieve tekst in een PPTX-presentatie. |
| [`find_shape(slide, alt_text)`](/slides/python-net/nl/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Zoek een vorm op basis van alternatieve tekst op een dia in een PPTX-presentatie. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/nl/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Wijzigt de plaatsing van alle vormen op de dia. Lijnt vormen uit op de marges of de rand van de dia<br/>            of lijnt ze uit ten opzichte van elkaar. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/nl/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Wijzigt de plaatsing van geselecteerde vormen op de dia. Lijnt vormen uit op de marges of de rand van de dia<br/>            of lijnt ze uit ten opzichte van elkaar. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/nl/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Wijzigt de plaatsing van alle vormen binnen een gegroepeerde vorm. Lijnt vormen uit op de marges of de rand van de dia<br/>            of lijnt ze uit ten opzichte van elkaar. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/nl/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Wijzigt de plaatsing van geselecteerde vormen binnen een gegroepeerde vorm. Lijnt vormen uit op de marges of de rand van de dia<br/>            of lijnt ze uit ten opzichte van elkaar. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/nl/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Zoekt alle vormen op de opgegeven dia die overeenkomen met het opgegeven placeholder-type. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/nl/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Zoekt en vervangt tekst in een presentatie met het opgegeven formaat |
| [`get_all_text_boxes(slide)`](/slides/python-net/nl/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Geeft alle tekstframes op een dia in een PPTX-presentatie terug. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/nl/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Geeft alle tekstframes op de opgegeven dia terug die de opgegeven tekst bevatten. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/nl/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Geeft alle tekstframes in een PPTX-presentatie terug. |
| [`to_save_format(format)`](/slides/python-net/nl/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Converteert een bronbestandformaat naar de overeenkomstige [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat). |

### Zie ook
* module [`aspose.slides.util`](/slides/python-net/nl/aspose.slides.util)
* bibliotheek [`Aspose.Slides`](/slides/python-net)