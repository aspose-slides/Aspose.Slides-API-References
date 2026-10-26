---
title: SlideUtil class
second_title: Aspose.Slides dla Pythona poprzez .NET - referencja API
description: 
type: docs
url: /pl/aspose.slides.util/slideutil/
---
## SlideUtil klasa

Udostępnia metody, które pomagają wyszukiwać kształty i tekst w prezentacji.

Typ SlideUtil udostępnia następujące elementy:

## Metody

| Metoda | Opis |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/pl/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Znajduje kształt po alternatywnym tekście w prezentacji PPTX. |
| [`find_shape(slide, alt_text)`](/slides/python-net/pl/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Znajduje kształt po alternatywnym tekście na slajdzie w prezentacji PPTX. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/pl/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Zmienia położenie wszystkich kształtów na slajdzie. Wyrównuje kształty do marginesów lub krawędzi slajdu<br/>            lub wyrównuje je względem siebie. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/pl/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Zmienia położenie wybranych kształtów na slajdzie. Wyrównuje kształty do marginesów lub krawędzi slajdu<br/>            lub wyrównuje je względem siebie. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/pl/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Zmienia położenie wszystkich kształtów w grupie kształtów. Wyrównuje kształty do marginesów lub krawędzi slajdu<br/>            lub wyrównuje je względem siebie. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/pl/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Zmienia położenie wybranych kształtów w grupie kształtów. Wyrównuje kształty do marginesów lub krawędzi slajdu<br/>            lub wyrównuje je względem siebie. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/pl/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Wyszukuje wszystkie kształty na wskazanym slajdzie, które pasują do podanego typu placeholdera. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/pl/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Znajduje i zamienia tekst w prezentacji przy użyciu podanego formatu |
| [`get_all_text_boxes(slide)`](/slides/python-net/pl/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Zwraca wszystkie ramki tekstowe na slajdzie w prezentacji PPTX. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/pl/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Zwraca wszystkie ramki tekstowe na wskazanym slajdzie, które zawierają podany tekst. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/pl/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Zwraca wszystkie ramki tekstowe w prezentacji PPTX. |
| [`to_save_format(format)`](/slides/python-net/pl/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Konwertuje format pliku źródłowego na odpowiadający [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat). |


### Zobacz także
* moduł [`aspose.slides.util`](/slides/python-net/pl/aspose.slides.util)
* biblioteka [`Aspose.Slides`](/slides/python-net)