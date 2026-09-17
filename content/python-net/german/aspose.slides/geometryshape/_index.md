---
title: GeometryShape class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/geometryshape/
---
## GeometryShape Klasse

Stellt die Basisklasse für alle geometrischen Formen dar.

**Inheritance:**[`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der GeometryShape-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/geometryshape/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur lesbar **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/geometryshape/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur lesbar [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/geometryshape/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/geometryshape/raw_frame/) | Gibt die Rohrahmen-Eigenschaften der Form zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/geometryshape/frame/) | Gibt die Rahmen-Eigenschaften der Form zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/geometryshape/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Linieneigenschaften besitzen.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/geometryshape/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen.<br/>            Nur lesbar [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/geometryshape/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet wurden.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen.<br/>            Nur lesbar [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/geometryshape/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Füll-Eigenschaften besitzen.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/geometryshape/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/geometryshape/hyperlink_mouse_over/) | Gibt den für Mauszeiger definierten Hyperlink zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/geometryshape/hyperlink_manager/) | Gibt den Hyperlink-Verwalter zurück.<br/>            Nur lesbar [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/geometryshape/hidden/) | Bestimmt, ob die Form verborgen ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/geometryshape/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form im hinteren Teil der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form im vorderen Teil der Z-Reihenfolge zurück.<br/>            Nur lesbar **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/geometryshape/connection_site_count/) | Gibt die Anzahl der Anschlusspunkte an der Form zurück.<br/>            Nur lesbar **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/geometryshape/rotation/) | Gibt die Anzahl der Grad zurück, um die angegebene Form um die Z-Achse gedreht ist, oder legt sie fest.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/geometryshape/x/) | Gibt die X-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest (gemessen in Punkten).<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/geometryshape/y/) | Gibt die Y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest (gemessen in Punkten).<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/geometryshape/width/) | Gibt die Breite der Form zurück oder legt sie fest (gemessen in Punkten).<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/geometryshape/height/) | Gibt die Höhe der Form zurück oder legt sie fest (gemessen in Punkten).<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/geometryshape/black_white_mode/) | Eigenschaft legt fest, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/geometryshape/unique_id/) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code bestimmt ist.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel behandelt werden.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/geometryshape/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der über die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/geometryshape/alternative_text/) | Gibt den alternativen Text, der mit einer Form verknüpft ist, zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/geometryshape/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/geometryshape/name/) | Gibt den Namen einer Form zurück oder legt ihn fest.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren String.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/geometryshape/is_decorative/) | Gibt die Option „Als dekorativ markieren“ zurück oder legt sie fest.<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/geometryshape/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IBaseShapeLock`](/slides/python-net/de/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/geometryshape/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur lesbar **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/geometryshape/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, falls die Form gruppiert ist. Gibt sonst None zurück.<br/>            Nur lesbar [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/geometryshape/slide/) | Gibt die übergeordnete Folie der Form zurück.<br/>            Nur lesbar [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/geometryshape/presentation/) | Gibt die übergeordnete Präsentation der Folie zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/de/aspose.slides/geometryshape/shape_style/) | Gibt das Stil-Objekt der Form zurück.<br/>            Nur lesbar [`IShapeStyle`](/slides/python-net/de/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type/) | Gibt den voreingestellten Geometrie-Typ zurück oder legt ihn fest.<br/>            Hinweis: Beim Ändern des Werts werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt.<br/>            Lesen/Schreiben [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/de/aspose.slides/geometryshape/adjustments/) | Gibt eine Sammlung der Anpassungswerte der Form zurück.<br/>            Nur lesbar [`IAdjustValueCollection`](/slides/python-net/de/aspose.slides/iadjustvaluecollection). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/geometryshape/get_image/#) | Gibt das Form-Miniaturbild zurück.<br/>            ShapeThumbnailBounds.Shape wird standardmäßig als Typ für die Miniaturbild-Grenzen verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | Gibt das Form-Miniaturbild zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | Speichert den Inhalt von Shape als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt von Shape als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/geometryshape/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und legt die Platzhalter-Eigenschaften auf einen angegebenen fest. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/geometryshape/get_base_placeholder/#) | Gibt eine Basis-Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt).<br/>            Gibt None zurück, wenn die aktuelle Form nicht vererbt wird. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/geometryshape/get_visual_bounds/#) | Liefert die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [`get_geometry_paths(self)`](/slides/python-net/de/aspose.slides/geometryshape/get_geometry_paths/#) | Gibt eine Kopie des Pfads der Geometrie-Form zurück. Koordinaten sind relativ zur oberen linken Ecke der Form. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/de/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | Aktualisiert die Geometrie der Form aus dem [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)-Objekt. Koordinaten müssen relativ zur linken<br/>             oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/de/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | Aktualisiert die Geometrie der Form aus dem Array von [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath). Koordinaten müssen relativ zur linken<br/>             oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/de/aspose.slides/geometryshape/create_shape_elements/#) | Erstellt und gibt ein Array der Form-Elemente zurück. |

### Siehe auch
* Klasse [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)