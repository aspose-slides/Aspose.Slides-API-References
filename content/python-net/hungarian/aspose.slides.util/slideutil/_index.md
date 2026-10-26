---
title: SlideUtil class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides.util/slideutil/
---
## SlideUtil osztály

Metódusokat kínál, amelyek segítenek alakzatok és szöveg keresésében egy prezentációban.

A SlideUtil típus a következő tagokat tartalmazza:

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/hu/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Alakzat keresése alternatív szöveg alapján egy PPTX prezentációban. |
| [`find_shape(slide, alt_text)`](/slides/python-net/hu/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Alakzat keresése alternatív szöveg alapján egy dián egy PPTX prezentációban. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/hu/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Módosítja az összes alakzat elhelyezését a dián. Igazítja az alakzatokat a margókhoz vagy a dia széléhez<br/>            vagy egymáshoz viszonyítva igazítja őket. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/hu/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Módosítja a kiválasztott alakzatok elhelyezését a dián. Igazítja az alakzatokat a margókhoz vagy a dia széléhez<br/>             vagy egymáshoz viszonyítva igazítja őket. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/hu/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Módosítja az összes alakzat elhelyezését a csoport alakzaton belül. Igazítja az alakzatokat a margókhoz vagy a dia széléhez<br/>            vagy egymáshoz viszonyítva igazítja őket. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/hu/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Módosítja a kiválasztott alakzatok elhelyezését egy csoport alakzaton belül. Igazítja az alakzatokat a margókhoz vagy a dia széléhez<br/>            vagy egymáshoz viszonyítva igazítja őket. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/hu/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Az összes alakzatot keresi a megadott dián, amelyek megfelelnek a megadott helyőrző típusnak. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/hu/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Megkeresi és helyettesíti a szöveget a prezentációban a megadott formátummal. |
| [`get_all_text_boxes(slide)`](/slides/python-net/hu/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Visszaadja az összes szövegkeretet egy dián egy PPTX prezentációban. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/hu/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Visszaadja az összes szövegkeretet a megadott dián, amelyek a megadott szöveget tartalmazzák. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/hu/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Visszaadja az összes szövegkeretet egy PPTX prezentációban. |
| [`to_save_format(format)`](/slides/python-net/hu/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Átalakítja a forrásfájl formátumát a megfelelő [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) formátumra. |

### Lásd még
* modul [`aspose.slides.util`](/slides/python-net/hu/aspose.slides.util)
* könyvtár [`Aspose.Slides`](/slides/python-net)