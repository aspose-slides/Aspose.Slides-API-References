---
title: ZoomObject class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/zoomobject/
---
## ZoomObject Klasse

Stellt ein Zoom-Objekt in einer Folie dar.

**Vererbung:**[`ZoomObject`](/slides/python-net/de/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der ZoomObject-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/zoomobject/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur lesbar **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/zoomobject/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur lesbar [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/zoomobject/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/zoomobject/raw_frame/) | Gibt die Eigenschaften des rohen Formrahmens zurück oder legt sie fest.<br/>            Lese/Schreibe [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/zoomobject/frame/) | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest.<br/>            Lese/Schreibe [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/zoomobject/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Linieneigenschaften besitzen, None zurückgeben.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/zoomobject/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen, None zurückgeben.<br/>            Nur lesbar [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/zoomobject/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte, die auf eine Form angewendet werden, enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen, None zurückgeben.<br/>            Nur lesbar [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/zoomobject/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Fülleigenschaften besitzen, None zurückgeben.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/zoomobject/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder legt ihn fest.<br/>            Lese/Schreibe [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/zoomobject/hyperlink_mouse_over/) | Gibt den für Mauszeiger-Überfahrt definierten Hyperlink zurück oder legt ihn fest.<br/>            Lese/Schreibe [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/zoomobject/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur lesbar [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/zoomobject/hidden/) | Bestimmt, ob die Form ausgeblendet ist.<br/>            Lese/Schreibe **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/zoomobject/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende der Z-Reihenfolge zurück.<br/>            Nur lesbar **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/zoomobject/connection_site_count/) | Gibt die Anzahl der Verbindungsstellen der Form zurück.<br/>            Nur lesbar **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/zoomobject/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder legt sie fest.<br/>            Ein positiver Wert bedeutet eine Drehung im Uhrzeigersinn; ein negativer Wert<br/>            bedeutet eine Drehung gegen den Uhrzeigersinn.<br/>            Lese/Schreibe **float**. |
| [`x`](/slides/python-net/de/aspose.slides/zoomobject/x/) | Liest oder setzt die X-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lese/Schreibe **float**. |
| [`y`](/slides/python-net/de/aspose.slides/zoomobject/y/) | Liest oder setzt die Y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lese/Schreibe **float**. |
| [`width`](/slides/python-net/de/aspose.slides/zoomobject/width/) | Liest oder setzt die Breite der Form, gemessen in Punkten.<br/>            Lese/Schreibe **float**. |
| [`height`](/slides/python-net/de/aspose.slides/zoomobject/height/) | Liest oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Lese/Schreibe **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/zoomobject/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeige-Modus dargestellt wird.<br/>            Lese/Schreibe [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/zoomobject/unique_id/) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als dauerhafter eindeutiger Schlüssel behandelt werden.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/zoomobject/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und<br/>            PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/zoomobject/alternative_text/) | Gibt den alternativen Text zurück, der mit einer Form verbunden ist, oder legt ihn fest.<br/>            Lese/Schreibe **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/zoomobject/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück, der mit einer Form verbunden ist, oder legt ihn fest.<br/>            Lese/Schreibe **str**. |
| [`name`](/slides/python-net/de/aspose.slides/zoomobject/name/) | Gibt den Namen einer Form zurück oder legt ihn fest.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren Zeichenfolgenwert.<br/>            Lese/Schreibe **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/zoomobject/is_decorative/) | Liest oder setzt die Option 'Als dekorativ kennzeichnen'<br/>            Lese/Schreibe **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/zoomobject/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/zoomobject/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur lesbar **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/zoomobject/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Nur lesbar [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/zoomobject/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Nur lesbar [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/zoomobject/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/de/aspose.slides/zoomobject/graphical_object_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/de/aspose.slides/zoomobject/image_type/) | Liest oder setzt den Bildtyp eines Zoom-Objekts.<br/>            Lese/Schreibe [`ZoomImageType`](/slides/python-net/de/aspose.slides/zoomimagetype).<br/>            Standardwert: Preview |
| [`return_to_parent`](/slides/python-net/de/aspose.slides/zoomobject/return_to_parent/) | Liest oder setzt das Navigationsverhalten in der Bildschirmpräsentation.<br/>            Lese/Schreibe **bool**.<br/>            Standardwert: false |
| [`show_background`](/slides/python-net/de/aspose.slides/zoomobject/show_background/) | Liest oder setzt den Wert, der angibt, ob der Zoom den Hintergrund der Ziel-Folie verwendet.<br/>            Lese/Schreibe **bool**.<br/>            Standardwert: true |
| [`zoom_image`](/slides/python-net/de/aspose.slides/zoomobject/zoom_image/) | Liest oder setzt das Bild für das Zoom-Objekt.<br/>            Lese/Schreibe [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/de/aspose.slides/zoomobject/transition_duration/) | Liest oder setzt die Dauer der Überblendung zwischen Zoom und Folie.<br/>            Lese/Schreibe **float**.<br/>            Standardwert: 1.0f |

## Methoden

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/zoomobject/get_image/#) | Gibt das Form-Vorschaubild zurück.<br/>            ShapeThumbnailBounds.Shape wird standardmäßig als Typ für die Vorschaubild-Grenzen verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | Gibt das Form-Vorschaubild zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/zoomobject/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/zoomobject/get_base_placeholder/#) | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt).<br/>            Wenn die aktuelle Form nicht vererbt ist, wird None zurückgegeben. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/zoomobject/get_visual_bounds/#) | Ermittelt die visuellen Grenzen der Form, die aus ihrem gerenderten Inhalt berechnet werden. |

### Siehe auch
* Klasse [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Klasse [`ZoomObject`](/slides/python-net/de/aspose.slides/zoomobject)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)