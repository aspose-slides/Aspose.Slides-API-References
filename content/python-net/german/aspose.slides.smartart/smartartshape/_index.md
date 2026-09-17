---
title: SmartArtShape class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.smartart/smartartshape/
---
## SmartArtShape Klasse

Stellt eine SmartArt-Form dar

**Vererbung:**[`SmartArtShape`](/slides/python-net/de/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der SmartArtShape-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides.smartart/smartartshape/is_text_holder/) | Bestimmt, ob die Form ein TextHolder_PPT ist.<br/>            Nur lesbar **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides.smartart/smartartshape/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur lesbar [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides.smartart/smartartshape/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides.smartart/smartartshape/raw_frame/) | Gibt die rohen Rahmen-Eigenschaften der Form zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides.smartart/smartartshape/frame/) | Gibt die Rahmen-Eigenschaften der Form zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides.smartart/smartartshape/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine Linien-Eigenschaften besitzen.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides.smartart/smartartshape/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen.<br/>            Nur lesbar [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides.smartart/smartartshape/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte auf eine Form anwendet.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen.<br/>            Nur lesbar [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides.smartart/smartartshape/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine Füll-Eigenschaften besitzen.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides.smartart/smartartshape/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | Gibt den für Mausover definierten Hyperlink zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides.smartart/smartartshape/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur lesbar [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides.smartart/smartartshape/hidden/) | Bestimmt, ob die Form ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides.smartart/smartartshape/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form ganz hinten in der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form ganz vorne in der Z-Reihenfolge zurück.<br/>            Nur lesbar **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides.smartart/smartartshape/connection_site_count/) | Gibt die Anzahl der Verbindungsstellen der Form zurück.<br/>            Nur lesbar **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides.smartart/smartartshape/rotation/) | Gibt die Anzahl der Grad zurück, um die angegebene Form um die Z-Achse gedreht ist, oder legt sie fest.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert<br/>            bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides.smartart/smartartshape/x/) | Liest oder setzt die X-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides.smartart/smartartshape/y/) | Liest oder setzt die Y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides.smartart/smartartshape/width/) | Liest oder setzt die Breite der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides.smartart/smartartshape/height/) | Liest oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides.smartart/smartartshape/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus dargestellt wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides.smartart/smartartshape/unique_id/) | Gibt einen internen, presentations-bezogenen Bezeichner zurück, der für Add-Ins oder anderen Code bestimmt ist.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als permanenter eindeutiger Schlüssel behandelt werden.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | Gibt einen Folien-bezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code erlaubt, die Form zuverlässig von überall im Dokument aus zu referenzieren.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides.smartart/smartartshape/alternative_text/) | Gibt den alternativen Text der Form zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides.smartart/smartartshape/alternative_text_title/) | Gibt den Titel des alternativen Textes der Form zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides.smartart/smartartshape/name/) | Gibt den Namen einer Form zurück oder legt ihn fest.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren String.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides.smartart/smartartshape/is_decorative/) | Liest oder setzt die Option 'Als dekorativ markieren'<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides.smartart/smartartshape/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IBaseShapeLock`](/slides/python-net/de/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides.smartart/smartartshape/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur lesbar **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides.smartart/smartartshape/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls None.<br/>            Nur lesbar [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides.smartart/smartartshape/slide/) | Gibt die übergeordnete Folie der Form zurück.<br/>            Nur lesbar [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides.smartart/smartartshape/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/de/aspose.slides.smartart/smartartshape/shape_style/) | Gibt das Stil-Objekt der Form zurück.<br/>            Nur lesbar [`IShapeStyle`](/slides/python-net/de/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/de/aspose.slides.smartart/smartartshape/shape_type/) | Liest oder setzt den vordefinierten Geometrie-Typ.<br/>            Hinweis: Beim Ändern des Wertes werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt.<br/>            Lesen/Schreiben [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/de/aspose.slides.smartart/smartartshape/adjustments/) | Gibt eine Sammlung der Anpassungswerte der Form zurück.<br/>            Nur lesbar [`IAdjustValueCollection`](/slides/python-net/de/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/de/aspose.slides.smartart/smartartshape/text_frame/) | Gibt den Text der SmartArt-Form zurück.<br/>            Nur lesbar [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/get_image/#) | Gibt das Vorschaubild der Form zurück.<br/>            ShapeThumbnailBounds.Shape wird standardmäßig als Typ für die Form-Vorschaubild-Grenzen verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | Gibt das Vorschaubild der Form zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt).<br/>            None wird zurückgegeben, wenn die aktuelle Form nicht geerbt ist. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | Ermittelt die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [`get_geometry_paths(self)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | Gibt eine Kopie des Pfades der geometrischen Form zurück. Koordinaten sind relativ zur oberen linken Ecke der Form. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | Aktualisiert die Geometrie der Form aus dem [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)-Objekt. Koordinaten müssen relativ zur linken<br/>             oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | Aktualisiert die Geometrie der Form aus einem Array von [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath). Koordinaten müssen relativ zur linken<br/>             oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/de/aspose.slides.smartart/smartartshape/create_shape_elements/#) | Erstellt und gibt ein Array der Form-Elemente zurück. |

### Siehe auch
* Klasse [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Klasse [`SmartArtShape`](/slides/python-net/de/aspose.slides.smartart/smartartshape)
* Modul [`aspose.slides.smartart`](/slides/python-net/de/aspose.slides.smartart)
* Bibliothek [`Aspose.Slides`](/slides/python-net)