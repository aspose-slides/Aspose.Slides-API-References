---
title: SectionZoomFrame class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame Klasse

Stellt ein Section Zoom-Objekt in einer Folie dar.

**Inheritance:**[`SectionZoomFrame`](/slides/python-net/de/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/de/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der Typ SectionZoomFrame stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/sectionzoomframe/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur lesbar **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/sectionzoomframe/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur lesbar [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/sectionzoomframe/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/sectionzoomframe/raw_frame/) | Gibt die rohen Eigenschaften des Formrahmens zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/sectionzoomframe/frame/) | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/sectionzoomframe/line_format/) | Gibt das LineFormat-Objekt zurück, das Linieneigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formen, die keine Linieneigenschaften haben.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/sectionzoomframe/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3-D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formen, die keine 3-D-Eigenschaften haben.<br/>            Nur lesbar [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/sectionzoomframe/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden.<br/>            Hinweis: kann None zurückgeben für bestimmte Formen, die keine Effekt-Eigenschaften haben.<br/>            Nur lesbar [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/sectionzoomframe/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformat-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formen, die keine Fülleigenschaften haben.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/sectionzoomframe/hyperlink_click/) | Gibt den definierten Hyperlink für einen Mausklick zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | Gibt den definierten Hyperlink für Maus-over zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/sectionzoomframe/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur lesbar [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/sectionzoomframe/hidden/) | Bestimmt, ob die Form ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/sectionzoomframe/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende der Z-Reihenfolge zurück.<br/>            Nur lesbar **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/sectionzoomframe/connection_site_count/) | Gibt die Anzahl der Verbindungsstellen an der Form zurück.<br/>            Nur lesbar **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/sectionzoomframe/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder legt sie fest.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/sectionzoomframe/x/) | Gibt die X-Koordinate der linken oberen Ecke der Form zurück oder legt sie fest (gemessen in Punkten).<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/sectionzoomframe/y/) | Gibt die Y-Koordinate der linken oberen Ecke der Form zurück oder legt sie fest (gemessen in Punkten).<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/sectionzoomframe/width/) | Gibt die Breite der Form zurück oder legt sie fest (gemessen in Punkten).<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/sectionzoomframe/height/) | Gibt die Höhe der Form zurück oder legt sie fest (gemessen in Punkten).<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/sectionzoomframe/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeigemodus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/sectionzoomframe/unique_id/) | Gibt einen internen, presentations-bezogenen Bezeichner zurück, der für Add-Ins oder anderen Code vorgesehen ist.<br/>            Da dieser Wert vom Nutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel behandelt werden.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/sectionzoomframe/office_interop_shape_id/) | Gibt einen folien-bezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, zuverlässig von überall im Dokument auf die Form zu verweisen.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/sectionzoomframe/alternative_text/) | Gibt den alternativen Text, der einer Form zugeordnet ist, zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/sectionzoomframe/alternative_text_title/) | Gibt den Titel des alternativen Textes, der einer Form zugeordnet ist, zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/sectionzoomframe/name/) | Gibt den Namen einer Form zurück oder legt ihn fest.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren Zeichenfolgenwert.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/sectionzoomframe/is_decorative/) | Gibt die Option „Als dekorativ markieren“ zurück oder legt sie fest<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/sectionzoomframe/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/sectionzoomframe/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur lesbar **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/sectionzoomframe/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Nur lesbar [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/sectionzoomframe/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Nur lesbar [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/sectionzoomframe/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/de/aspose.slides/sectionzoomframe/graphical_object_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/de/aspose.slides/sectionzoomframe/image_type/) | Gibt den Bildtyp eines Zoom-Objekts zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`ZoomImageType`](/slides/python-net/de/aspose.slides/zoomimagetype).<br/>            Standardwert: Preview |
| [`return_to_parent`](/slides/python-net/de/aspose.slides/sectionzoomframe/return_to_parent/) | Gibt das Navigationsverhalten in der Diashow zurück oder legt es fest.<br/>            Lesen/Schreiben **bool**.<br/>            Standardwert: false |
| [`show_background`](/slides/python-net/de/aspose.slides/sectionzoomframe/show_background/) | Gibt an, ob der Zoom den Hintergrund der Ziel-Folien verwendet, oder legt dies fest.<br/>            Lesen/Schreiben **bool**.<br/>            Standardwert: true |
| [`zoom_image`](/slides/python-net/de/aspose.slides/sectionzoomframe/zoom_image/) | Gibt das Bild für das Zoom-Objekt zurück oder legt es fest.<br/>            Lesen/Schreiben [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/de/aspose.slides/sectionzoomframe/transition_duration/) | Gibt die Dauer des Übergangs zwischen Zoom und Folie zurück oder legt sie fest.<br/>            Lesen/Schreiben **float**.<br/>            Standardwert: 1.0f |
| [`target_section`](/slides/python-net/de/aspose.slides/sectionzoomframe/target_section/) | Gibt das Abschnitts-Objekt zurück, zu dem das Section-Zoom-Objekt verlinkt, oder legt es fest.<br/>            Lesen/Schreiben [`ISection`](/slides/python-net/de/aspose.slides/isection). |

## Methoden

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/sectionzoomframe/get_image/#) | Gibt das Miniaturbild der Form zurück.<br/>            ShapeThumbnailBounds.Shape Miniaturbild-Grenztyp wird standardmäßig verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | Gibt das Miniaturbild der Form zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/sectionzoomframe/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/sectionzoomframe/get_base_placeholder/#) | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt).<br/>            Gibt None zurück, wenn die aktuelle Form nicht vererbt ist. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/sectionzoomframe/get_visual_bounds/#) | Gibt die visuellen Grenzen der Form zurück, ermittelt aus ihrem gerenderten Inhalt. |

### Siehe auch
* Klasse [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject)
* Klasse [`SectionZoomFrame`](/slides/python-net/de/aspose.slides/sectionzoomframe)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Klasse [`ZoomObject`](/slides/python-net/de/aspose.slides/zoomobject)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)