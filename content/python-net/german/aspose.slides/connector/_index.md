---
title: Connector class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/connector/
---
## Connector Klasse

Stellt einen Connector dar.

**Inheritance:**[`Connector`](/slides/python-net/de/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der Connector-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/connector/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur lesbar **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/connector/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur lesbar [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/connector/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/connector/raw_frame/) | Gibt die rohen Frame-Eigenschaften der Form zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/connector/frame/) | Gibt die Frame-Eigenschaften der Form zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/connector/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Linieneigenschaften besitzen.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/connector/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen.<br/>            Nur lesbar [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/connector/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte, die auf eine Form angewendet werden, enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen.<br/>            Nur lesbar [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/connector/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Fülleigenschaften besitzen.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/connector/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/connector/hyperlink_mouse_over/) | Gibt den für Mausüberfahren definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/connector/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur lesbar [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/connector/hidden/) | Bestimmt, ob die Form verborgen ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/connector/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form ganz hinten in der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form ganz vorne in der Z-Reihenfolge zurück.<br/>            Nur lesbar **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/connector/connection_site_count/) | Gibt die Anzahl der Verbindungspunkte an der Form zurück.<br/>            Nur lesbar **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/connector/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/connector/x/) | Liest oder setzt die x-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/connector/y/) | Liest oder setzt die y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/connector/width/) | Liest oder setzt die Breite der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/connector/height/) | Liest oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/connector/black_white_mode/) | Eigenschaft legt fest, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/connector/unique_id/) | Gibt einen internen, presentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist.<br/>            Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als dauerhaft eindeutiger Schlüssel behandelt werden.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/connector/office_interop_shape_id/) | Gibt einen Folien-bezogenen eindeutigen Bezeichner zurück, der während der Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/connector/alternative_text/) | Gibt den alternativen Text, der mit einer Form verknüpft ist, zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/connector/alternative_text_title/) | Gibt den Titel des alternativen Texts, der mit einer Form verknüpft ist, zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/connector/name/) | Gibt den Namen einer Form zurück oder setzt ihn.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren String.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/connector/is_decorative/) | Liest oder setzt die Option 'Als dekorativ markieren'<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/connector/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IConnectorLock`](/slides/python-net/de/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/connector/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur lesbar **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/connector/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls gibt es None zurück.<br/>            Nur lesbar [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/connector/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Nur lesbar [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/connector/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/de/aspose.slides/connector/shape_style/) | Gibt das Stilobjekt der Form zurück.<br/>            Nur lesbar [`IShapeStyle`](/slides/python-net/de/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/de/aspose.slides/connector/shape_type/) | Gibt den AutoShape-Typ zurück oder setzt ihn.<br/>            Lesen/Schreiben [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/de/aspose.slides/connector/adjustments/) | Gibt eine Sammlung von Anpassungswerten der Form zurück.<br/>            Nur lesbar [`IAdjustValueCollection`](/slides/python-net/de/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/de/aspose.slides/connector/connector_lock/) | Gibt die Sperren des Connectors zurück.<br/>            Nur lesbar [`IConnectorLock`](/slides/python-net/de/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/de/aspose.slides/connector/start_shape_connected_to/) | Gibt die Form zurück, an die der Anfang des Connectors angehängt wird, oder setzt sie.<br/>            Lesen/Schreiben [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/de/aspose.slides/connector/end_shape_connected_to/) | Gibt die Form zurück, an die das Ende des Connectors angehängt wird, oder setzt sie.<br/>            Lesen/Schreiben [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/de/aspose.slides/connector/start_shape_connection_site_index/) | Gibt den Index des Verbindungspunktes für die Startform zurück oder setzt ihn.<br/>            Lesen/Schreiben **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/de/aspose.slides/connector/end_shape_connection_site_index/) | Gibt den Index des Verbindungspunktes für die Endform zurück oder setzt ihn.<br/>            Lesen/Schreiben **int**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/connector/get_image/#) | Gibt ein Form-Thumbnail zurück.<br/>            Der Standard ist der Typ ShapeThumbnailBounds.Shape für die Thumbnail-Grenzen. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Gibt ein Form-Thumbnail zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/connector/write_as_svg/#iorawiobase) | Speichert den Inhalt einer Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt einer Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/connector/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/connector/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/connector/get_base_placeholder/#) | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Master-Folie, von der die aktuelle Form erbt).<br/>            Gibt None zurück, wenn die aktuelle Form nicht vererbt wird. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/connector/get_visual_bounds/#) | Liest die visuellen Grenzen der Form, die aus ihrem gerenderten Inhalt berechnet werden. |
| [`get_geometry_paths(self)`](/slides/python-net/de/aspose.slides/connector/get_geometry_paths/#) | Gibt eine Kopie des Pfads der geometrischen Form zurück. Koordinaten sind relativ zur linken oberen Ecke der Form. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/de/aspose.slides/connector/set_geometry_path/#igeometrypath) | Aktualisiert die Formgeometrie aus dem [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)-Objekt. Koordinaten müssen relativ zur linken<br/>             oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/de/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Aktualisiert die Formgeometrie aus einem Array von [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath). Koordinaten müssen relativ zur linken<br/>             oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/de/aspose.slides/connector/create_shape_elements/#) | Erstellt und gibt ein Array der Form-Elemente zurück. |
| [`reroute(self)`](/slides/python-net/de/aspose.slides/connector/reroute/#) | Leitet den Connector um, sodass er den kürzest möglichen Pfad zwischen den Formen, die er verbindet, nimmt. |

### Siehe auch
* Klasse [`Connector`](/slides/python-net/de/aspose.slides/connector)
* Klasse [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)