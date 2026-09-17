---
title: ZoomFrame class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/zoomframe/
---
## ZoomFrame Klasse

Stellt ein Slide-Zoom-Objekt in einer Folie dar.

**Vererbung:**[`ZoomFrame`](/slides/python-net/de/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/de/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der ZoomFrame-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/zoomframe/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur lesbar **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/zoomframe/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur lesbar [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/zoomframe/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/zoomframe/raw_frame/) | Gibt die rohen Formrahmen-Eigenschaften zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/zoomframe/frame/) | Gibt die Formrahmen-Eigenschaften zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/zoomframe/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Linieneigenschaften besitzen, None zurückgeben.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/zoomframe/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3-D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine 3-D-Eigenschaften besitzen, None zurückgeben.<br/>            Nur lesbar [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/zoomframe/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte auf eine Form anwendet.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen, None zurückgeben.<br/>            Nur lesbar [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/zoomframe/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Fülleigenschaften besitzen, None zurückgeben.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/zoomframe/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/zoomframe/hyperlink_mouse_over/) | Gibt den für Maus-over definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/zoomframe/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur lesbar [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/zoomframe/hidden/) | Bestimmt, ob die Form ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/zoomframe/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form am Anfang der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form am Ende der Z-Reihenfolge zurück.<br/>            Nur lesbar **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/zoomframe/connection_site_count/) | Gibt die Anzahl der Verbindungsstellen auf der Form zurück.<br/>            Nur lesbar **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/zoomframe/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie.<br/>            Ein positiver Wert bedeutet eine Drehung im Uhrzeigersinn; ein negativer Wert<br/>            bedeutet eine Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/zoomframe/x/) | Gibt die X-Koordinate der oberen linken Ecke der Form zurück oder setzt sie, gemessen in Punkt.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/zoomframe/y/) | Gibt die Y-Koordinate der oberen linken Ecke der Form zurück oder setzt sie, gemessen in Punkt.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/zoomframe/width/) | Gibt die Breite der Form zurück oder setzt sie, gemessen in Punkt.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/zoomframe/height/) | Gibt die Höhe der Form zurück oder setzt sie, gemessen in Punkt.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/zoomframe/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus dargestellt wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/zoomframe/unique_id/) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code bestimmt ist.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als dauerhafter eindeutiger Schlüssel behandelt werden.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/zoomframe/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und<br/>            PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/zoomframe/alternative_text/) | Gibt den alternativen Text, der mit einer Form verbunden ist, zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/zoomframe/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück, der mit einer Form verbunden ist, oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/zoomframe/name/) | Gibt den Namen einer Form zurück oder setzt ihn.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren String.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/zoomframe/is_decorative/) | Gibt die Option 'Als dekorativ markieren' zurück oder setzt sie<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/zoomframe/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/zoomframe/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur lesbar **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/zoomframe/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Nur lesbar [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/zoomframe/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Nur lesbar [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/zoomframe/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/de/aspose.slides/zoomframe/graphical_object_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/de/aspose.slides/zoomframe/image_type/) | Gibt den Bildtyp eines Zoom-Objekts zurück oder setzt ihn.<br/>            Lesen/Schreiben [`ZoomImageType`](/slides/python-net/de/aspose.slides/zoomimagetype).<br/>            Standardwert: Preview |
| [`return_to_parent`](/slides/python-net/de/aspose.slides/zoomframe/return_to_parent/) | Gibt das Navigationsverhalten in der Bildschirmlaufzeit zurück oder setzt es.<br/>            Lesen/Schreiben **bool**.<br/>            Standardwert: false |
| [`show_background`](/slides/python-net/de/aspose.slides/zoomframe/show_background/) | Gibt den Wert zurück, der festlegt, ob der Zoom den Hintergrund der Zielfolie verwendet, oder setzt ihn.<br/>            Lesen/Schreiben **bool**.<br/>            Standardwert: true |
| [`zoom_image`](/slides/python-net/de/aspose.slides/zoomframe/zoom_image/) | Gibt das Bild für das Zoom-Objekt zurück oder setzt es.<br/>            Lesen/Schreiben [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/de/aspose.slides/zoomframe/transition_duration/) | Gibt die Dauer der Transition zwischen Zoom und Folie zurück oder setzt sie.<br/>            Lesen/Schreiben **float**.<br/>            Standardwert: 1.0f |
| [`target_slide`](/slides/python-net/de/aspose.slides/zoomframe/target_slide/) | Gibt das Folienobjekt zurück, auf das das Slide-Zoom-Objekt verlinkt, oder setzt es.<br/>            Lesen/Schreiben [`ISlide`](/slides/python-net/de/aspose.slides/islide). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/zoomframe/get_image/#) | Gibt die Miniaturansicht der Form zurück.<br/>            ShapeThumbnailBounds.Shape wird standardmäßig als Typ für die Miniaturansichts-Grenzen verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | Gibt die Miniaturansicht der Form zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/zoomframe/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/zoomframe/get_base_placeholder/#) | Gibt eine einfache Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt).<br/>            Wenn die aktuelle Form nicht geerbt wird, wird None zurückgegeben. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/zoomframe/get_visual_bounds/#) | Gibt die visuellen Grenzen der Form zurück, berechnet aus ihrem gerenderten Inhalt. |

### Siehe auch
* Klasse [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Klasse [`ZoomFrame`](/slides/python-net/de/aspose.slides/zoomframe)
* Klasse [`ZoomObject`](/slides/python-net/de/aspose.slides/zoomobject)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)