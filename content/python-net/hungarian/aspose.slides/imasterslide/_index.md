---
title: IMasterSlide class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/imasterslide/
---
## IMasterSlide osztály

Egy mester diát képvisel egy bemutatóban.

Az IMasterSlide típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/imasterslide/header_footer_manager/) | Visszaadja a mester dia HeaderFooter kezelőjét.<br/>            Csak olvasható [`IMasterSlideHeaderFooterManager`](/slides/python-net/hu/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/hu/aspose.slides/imasterslide/title_style/) | Visszaadja a cím szöveg stílusát.<br/>            Csak olvasható [`ITextStyle`](/slides/python-net/hu/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/hu/aspose.slides/imasterslide/body_style/) | Visszaadja a törzs szöveg stílusát.<br/>            Csak olvasható [`ITextStyle`](/slides/python-net/hu/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/hu/aspose.slides/imasterslide/other_style/) | Visszaadja egy másik szöveg stílusát.<br/>            Csak olvasható [`ITextStyle`](/slides/python-net/hu/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/hu/aspose.slides/imasterslide/layout_slides/) | Visszaadja ennek a mester diának a gyermek elrendezés diák gyűjteményét.<br/>            Csak olvasható [`IMasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/hu/aspose.slides/imasterslide/preserve/) | Meghatározza, hogy a megfelelő mester törlésre kerül-e, amikor az összes <br/>            a mesterhez tartozó diák törlésre kerülnek.<br/>            Megjegyzés: Aspose.Slides soha nem távolítja el önmagától a nem használt mestert, <br/>            a nem használt mesterek tényleges eltávolításához hívd meg a **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Olvasás/írás **bool**. |
| [`has_depending_slides`](/slides/python-net/hu/aspose.slides/imasterslide/has_depending_slides/) | Visszaadja, hogy igaz, ha legalább egy dia függ ettől a mester diától.<br/>            Csak olvasható **bool**. |
| [`drawing_guides`](/slides/python-net/hu/aspose.slides/imasterslide/drawing_guides/) | Visszaadja a mester dia rajzolósegélyek gyűjteményét.<br/>            Csak olvasható [`IDrawingGuidesCollection`](/slides/python-net/hu/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/hu/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/hu/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/hu/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/hu/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/hu/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/hu/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/hu/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/hu/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/hu/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/hu/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/hu/aspose.slides/imasterslide/theme_manager/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/hu/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Létrehoz egy új mester diát a jelenlegi alapján, külső témát alkalmaz rá <br/>            és az elkészített mester diát minden függő diára alkalmazza. |
| [`get_depending_slides(self)`](/slides/python-net/hu/aspose.slides/imasterslide/get_depending_slides/#) | Visszaad egy tömböt az összes diákkal, amelyek függnek ettől a mester diától. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hu/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/hu/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/hu/aspose.slides/imasterslide/create_theme_effective/#) |  |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)