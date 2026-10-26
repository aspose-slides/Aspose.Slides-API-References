---
title: AutoShape class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/autoshape/
---
## AutoShape Klasse

Stellt ein AutoShape dar.

**Inheritance:**[`AutoShape`](/slides/python-net/de/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der AutoShape-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/autoshape/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur lesbar **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/autoshape/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur lesbar [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/autoshape/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/autoshape/raw_frame/) | Gibt die rohen Eigenschaften des Formrahmens zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/autoshape/frame/) | Gibt die Eigenschaften des Formrahmens zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/autoshape/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Linieneigenschaften besitzen.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/autoshape/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3-D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine 3-D-Eigenschaften besitzen.<br/>            Nur lesbar [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/autoshape/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte einer Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen.<br/>            Nur lesbar [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/autoshape/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Fülleigenschaften besitzen.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/autoshape/hyperlink_click/) | Liest oder setzt den für Mausklick definierten Hyperlink.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/autoshape/hyperlink_mouse_over/) | Liest oder setzt den für Maus-over definierten Hyperlink.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/autoshape/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur lesbar [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/autoshape/hidden/) | Bestimmt, ob die Form versteckt ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/autoshape/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form zurück, die sich am Ende der Z-Reihenfolge befindet,<br/>            und Shapes[Shapes.Count - 1] gibt die Form zurück, die sich an der Vorderseite der Z-Reihenfolge befindet.<br/>            Nur lesbar **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/autoshape/connection_site_count/) | Gibt die Anzahl der Verbindungspunkte auf der Form zurück.<br/>            Nur lesbar **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/autoshape/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/autoshape/x/) | Erhält oder setzt die x-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/autoshape/y/) | Erhält oder setzt die y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/autoshape/width/) | Erhält oder setzt die Breite der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/autoshape/height/) | Erhält oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/autoshape/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeige-Modus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/autoshape/unique_id/) | Gibt einen internen, presentationsbezogenen Bezeichner zurück, der für Add-ins oder anderen Code vorgesehen ist.<br/>            Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel behandelt werden.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/autoshape/office_interop_shape_id/) | Gibt einen Folien-bezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, zuverlässig von überall im Dokument auf die Form zu verweisen.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/autoshape/alternative_text/) | Liest oder setzt den alternativen Text einer Form.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/autoshape/alternative_text_title/) | Liest oder setzt den Titel des alternativen Textes einer Form.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/autoshape/name/) | Liest oder setzt den Namen einer Form.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren String.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/autoshape/is_decorative/) | Erhält oder setzt die Option 'Als dekorativ markieren'<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/autoshape/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IAutoShapeLock`](/slides/python-net/de/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/autoshape/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur lesbar **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/autoshape/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls gibt sie None zurück.<br/>            Nur lesbar [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/autoshape/slide/) | Gibt die übergeordnete Folie der Form zurück.<br/>            Nur lesbar [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/autoshape/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/de/aspose.slides/autoshape/shape_style/) | Gibt das Stil-Objekt der Form zurück.<br/>            Nur lesbar [`IShapeStyle`](/slides/python-net/de/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/de/aspose.slides/autoshape/shape_type/) | Gibt den voreingestellten Geometrie-Typ zurück oder setzt ihn.<br/>            Hinweis: Beim Ändern des Wertes werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt.<br/>            Lesen/Schreiben [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/de/aspose.slides/autoshape/adjustments/) | Gibt eine Sammlung der Anpassungswerte der Form zurück.<br/>            Nur lesbar [`IAdjustValueCollection`](/slides/python-net/de/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/de/aspose.slides/autoshape/auto_shape_lock/) | Gibt die Sperren des AutoShape zurück.<br/>            Nur lesbar [`IAutoShapeLock`](/slides/python-net/de/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/de/aspose.slides/autoshape/text_frame/) | Gibt das TextFrame-Objekt für das AutoShape zurück.<br/>            Nur lesbar [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/de/aspose.slides/autoshape/use_background_fill/) | Bestimmt, ob dieses AutoShape mit dem Folien-Hintergrundfüllung statt durch Stil oder FillFormat gefüllt werden soll.<br/>            Lesen/Schreiben **bool**. |
| [`is_text_box`](/slides/python-net/de/aspose.slides/autoshape/is_text_box/) | Gibt an, ob die Form ein Textfeld ist. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/autoshape/get_image/#) | Gibt das Miniaturbild der Form zurück.<br/>            Der Typ ShapeThumbnailBounds.Shape für die Miniaturbildgrenzen wird standardmäßig verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Gibt das Miniaturbild der Form zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/autoshape/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/autoshape/get_base_placeholder/#) | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt).<br/>            None wird zurückgegeben, wenn die aktuelle Form nicht vererbt wird. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/autoshape/get_visual_bounds/#) | Ermittelt die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [`get_geometry_paths(self)`](/slides/python-net/de/aspose.slides/autoshape/get_geometry_paths/#) | Gibt eine Kopie des Pfads der geometrischen Form zurück. Koordinaten sind relativ zur linken oberen Ecke der Form. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/de/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Aktualisiert die Geometrie der Form aus dem [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)-Objekt. Koordinaten müssen relativ zur linken oberen Ecke der Form sein.<br/>            Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/de/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Aktualisiert die Geometrie der Form aus einem Array von [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath). Koordinaten müssen relativ zur linken oberen Ecke der Form sein.<br/>            Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/de/aspose.slides/autoshape/create_shape_elements/#) | Erstellt und gibt ein Array der Form-Elemente zurück. |
| [`add_text_frame(self, text)`](/slides/python-net/de/aspose.slides/autoshape/add_text_frame/#str) | Fügt einer Form ein neues TextFrame hinzu.<br/>            Wenn die Form bereits ein TextFrame hat, wird einfach ihr Text geändert. |

### Siehe auch
* Klasse [`AutoShape`](/slides/python-net/de/aspose.slides/autoshape)
* Klasse [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)