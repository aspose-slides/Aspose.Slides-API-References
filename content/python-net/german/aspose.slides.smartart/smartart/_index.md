---
title: SmartArt class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.smartart/smartart/
---
## SmartArt-Klasse

Stellt ein SmartArt-Diagramm dar

**Vererbung:**[`SmartArt`](/slides/python-net/de/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der SmartArt-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides.smartart/smartart/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur lesen **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides.smartart/smartart/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur lesen [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides.smartart/smartart/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur lesen [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides.smartart/smartart/raw_frame/) | Gibt die rohen Eigenschaften des Formrahmens zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides.smartart/smartart/frame/) | Gibt die Eigenschaften des Formrahmens zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides.smartart/smartart/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Linieneigenschaften besitzen, None zurückgeben.<br/>            Nur lesen [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides.smartart/smartart/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen, None zurückgeben.<br/>            Nur lesen [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides.smartart/smartart/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet werden.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen, None zurückgeben.<br/>            Nur lesen [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides.smartart/smartart/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Füll-Eigenschaften besitzen, None zurückgeben.<br/>            Nur lesen [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides.smartart/smartart/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | Gibt den für Mausüberfahrt definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides.smartart/smartart/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur lesen [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides.smartart/smartart/hidden/) | Bestimmt, ob die Form ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides.smartart/smartart/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende der Z-Reihenfolge zurück.<br/>            Nur lesen **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides.smartart/smartart/connection_site_count/) | Gibt die Anzahl der Verbindungspunkte an der Form zurück.<br/>            Nur lesen **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides.smartart/smartart/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides.smartart/smartart/x/) | Liest oder schreibt die X-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides.smartart/smartart/y/) | Liest oder schreibt die Y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides.smartart/smartart/width/) | Liest oder schreibt die Breite der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides.smartart/smartart/height/) | Liest oder schreibt die Höhe der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides.smartart/smartart/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeigemodus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides.smartart/smartart/unique_id/) | Gibt einen internen, präsenzbezogenen Bezeichner zurück, der für die Verwendung durch Add-Ins oder anderen Code vorgesehen ist.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als dauerhafter eindeutiger Schlüssel behandelt werden.<br/>            Nur lesen **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides.smartart/smartart/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und<br/>            PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren.<br/>            Nur lesen **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides.smartart/smartart/alternative_text/) | Gibt den alternativen Text, der einer Form zugeordnet ist, zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides.smartart/smartart/alternative_text_title/) | Gibt den Titel des alternativen Textes, der einer Form zugeordnet ist, zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides.smartart/smartart/name/) | Gibt den Namen einer Form zurück oder setzt ihn.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf den leeren Zeichenkettenwert.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides.smartart/smartart/is_decorative/) | Liest oder schreibt die Option 'Als dekorativ markieren'<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides.smartart/smartart/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesen [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides.smartart/smartart/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur lesen **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides.smartart/smartart/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Nur lesen [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides.smartart/smartart/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Nur lesen [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides.smartart/smartart/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur lesen [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/de/aspose.slides.smartart/smartart/graphical_object_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesen [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/de/aspose.slides.smartart/smartart/all_nodes/) | Gibt Sammlungen aller Knoten im SmartArt-Objekt zurück.<br/>            Nur lesen [`ISmartArtNodeCollection`](/slides/python-net/de/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/de/aspose.slides.smartart/smartart/nodes/) | Gibt Sammlungen der Wurzelknoten im SmartArt-Objekt zurück.<br/>            Nur lesen [`ISmartArtNodeCollection`](/slides/python-net/de/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/de/aspose.slides.smartart/smartart/layout/) | Gibt das Layout des SmartArt-Objekts zurück oder setzt es.<br/>            Lesen/Schreiben [`SmartArtLayoutType`](/slides/python-net/de/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/de/aspose.slides.smartart/smartart/quick_style/) | Gibt den Schnellstil des SmartArt-Objekts zurück oder setzt ihn.<br/>            Lesen/Schreiben [`SmartArtQuickStyleType`](/slides/python-net/de/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/de/aspose.slides.smartart/smartart/color_style/) | Gibt den Farbstil des SmartArt-Objekts zurück oder setzt ihn.<br/>            Lesen/Schreiben [`SmartArtColorType`](/slides/python-net/de/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/de/aspose.slides.smartart/smartart/is_reversed/) | Gibt den Zustand des SmartArt-Diagramms in Bezug auf (von links nach rechts) LTR oder (von rechts nach links) RTL zurück oder setzt ihn, falls das Diagramm eine Umkehr unterstützt.<br/>            Lesen/Schreiben **bool**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides.smartart/smartart/get_image/#) | Gibt die Miniaturansicht der Form zurück.<br/>            ShapeThumbnailBounds.Shape wird standardmäßig als Typ für die Miniaturansichtsgrenzen verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | Gibt die Miniaturansicht der Form zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides.smartart/smartart/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides.smartart/smartart/get_base_placeholder/#) | Gibt eine einfache Platzhalterform zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form geerbt wird).<br/>            None wird zurückgegeben, wenn die aktuelle Form nicht geerbt ist. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides.smartart/smartart/get_visual_bounds/#) | Ermittelt die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |

### Siehe auch
* Klasse [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Klasse [`SmartArt`](/slides/python-net/de/aspose.slides.smartart/smartart)
* Modul [`aspose.slides.smartart`](/slides/python-net/de/aspose.slides.smartart)
* Bibliothek [`Aspose.Slides`](/slides/python-net)