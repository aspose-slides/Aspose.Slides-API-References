---
title: IMasterSlide class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/imasterslide/
---
## IMasterSlide Klasse

Stellt eine Masterfolie in einer Präsentation dar.

Der Typ IMasterSlide stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/imasterslide/header_footer_manager/) | Gibt den HeaderFooter-Manager der Masterfolie zurück.<br/>            Nur lesbar [`IMasterSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/de/aspose.slides/imasterslide/title_style/) | Gibt den Stil des Titeltexts zurück.<br/>            Nur lesbar [`ITextStyle`](/slides/python-net/de/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/de/aspose.slides/imasterslide/body_style/) | Gibt den Stil des Fließtextes zurück.<br/>            Nur lesbar [`ITextStyle`](/slides/python-net/de/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/de/aspose.slides/imasterslide/other_style/) | Gibt den Stil eines anderen Textes zurück.<br/>            Nur lesbar [`ITextStyle`](/slides/python-net/de/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/de/aspose.slides/imasterslide/layout_slides/) | Gibt die Sammlung der untergeordneten Layout-Folien für diese Masterfolie zurück.<br/>            Nur lesbar [`IMasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/de/aspose.slides/imasterslide/preserve/) | Bestimmt, ob die entsprechende Masterfolie gelöscht wird, wenn alle <br/>            Folien, die dieser Masterfolie folgen, gelöscht werden.<br/>            Hinweis: Aspose.Slides entfernt niemals automatisch unbenutzte Masterfolien, <br/>            um unbenutzte Masterfolien tatsächlich zu entfernen, rufen Sie **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Lesen/Schreiben **bool**. |
| [`has_depending_slides`](/slides/python-net/de/aspose.slides/imasterslide/has_depending_slides/) | Gibt **true** zurück, wenn mindestens eine Folie von dieser Masterfolie abhängt.<br/>            Nur lesbar **bool**. |
| [`drawing_guides`](/slides/python-net/de/aspose.slides/imasterslide/drawing_guides/) | Gibt eine Sammlung von Zeichenhilfen für die Masterfolie zurück.<br/>            Nur lesbar [`IDrawingGuidesCollection`](/slides/python-net/de/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/de/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/de/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/de/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/de/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/de/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/de/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/de/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/de/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/de/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/de/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/de/aspose.slides/imasterslide/theme_manager/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/de/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Erstellt eine neue Masterfolie basierend auf der aktuellen, wendet ein externes Design darauf an <br/>            und wendet die erstellte Masterfolie auf alle abhängigen Folien an. |
| [`get_depending_slides(self)`](/slides/python-net/de/aspose.slides/imasterslide/get_depending_slides/#) | Gibt ein Array mit allen Folien zurück, die von dieser Masterfolie abhängen. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/de/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/de/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides/imasterslide/create_theme_effective/#) |  |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)