---
title: SlideUtil class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.util/slideutil/
---
## SlideUtil Klasse

Bietet Methoden, die bei der Suche nach Formen und Text in einer Präsentation helfen.

Der Typ SlideUtil stellt die folgenden Mitglieder bereit:

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/de/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Findet die Form anhand des Alternativtextes in einer PPTX-Präsentation. |
| [`find_shape(slide, alt_text)`](/slides/python-net/de/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Findet die Form anhand des Alternativtextes auf einer Folie in einer PPTX-Präsentation. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/de/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Ändert die Position aller Formen auf der Folie. Richtet Formen an den Rändern oder am Rand der Folie aus<br/>            oder richtet sie relativ zueinander aus. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/de/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Ändert die Position ausgewählter Formen auf der Folie. Richtet Formen an den Rändern oder am Rand der Folie aus<br/>            oder richtet sie relativ zueinander aus. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/de/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Ändert die Position aller Formen innerhalb einer Gruppierung. Richtet Formen an den Rändern oder am Rand der Folie aus<br/>            oder richtet sie relativ zueinander aus. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/de/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Ändert die Position ausgewählter Formen innerhalb einer Gruppierung. Richtet Formen an den Rändern oder am Rand der Folie aus<br/>            oder richtet sie relativ zueinander aus. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/de/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Sucht alle Formen auf der angegebenen Folie, die dem angegebenen Platzhaltertyp entsprechen. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/de/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Findet und ersetzt Text in der Präsentation mit dem angegebenen Format. |
| [`get_all_text_boxes(slide)`](/slides/python-net/de/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Gibt alle Textfelder auf einer Folie in einer PPTX-Präsentation zurück. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/de/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Gibt alle Textfelder auf der angegebenen Folie zurück, die den angegebenen Text enthalten. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/de/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Gibt alle Textfelder in einer PPTX-Präsentation zurück. |
| [`to_save_format(format)`](/slides/python-net/de/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Konvertiert ein Quelldateiformat in das entsprechende [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat). |

### Siehe auch
* Modul [`aspose.slides.util`](/slides/python-net/de/aspose.slides.util)
* Bibliothek [`Aspose.Slides`](/slides/python-net)