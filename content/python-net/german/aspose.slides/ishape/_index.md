---
title: IShape class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishape/
---
## IShape Klasse

Represents a shape on a slide.

The IShape type exposes the following members:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/ishape/is_text_holder/) | Bestimmt, ob die Form ein TextHolder ist.<br/>            Schreibgeschützt **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/ishape/placeholder/) | Gibt den Platzhalter für eine Form zurück.<br/>            Schreibgeschützt [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/ishape/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Schreibgeschützt [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/ishape/raw_frame/) | Gibt die rohen Frame-Eigenschaften der Form zurück oder legt sie fest.<br/>            Lese-/Schreib [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/ishape/frame/) | Gibt die Frame-Eigenschaften der Form zurück oder legt sie fest.<br/>            Lese-/Schreib [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/ishape/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformat-Eigenschaften für eine Form enthält.<br/>            Schreibgeschützt [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/ishape/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das Linienformat-Eigenschaften für eine Form enthält.<br/>            Schreibgeschützt [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/ishape/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte auf eine Form anwendet.<br/>            Schreibgeschützt [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/ishape/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformat-Eigenschaften für eine Form enthält.<br/>            Schreibgeschützt [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/de/aspose.slides/ishape/hidden/) | Bestimmt, ob die Form versteckt ist.<br/>            Lese-/Schreib **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/ishape/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende der Z-Reihenfolge zurück.<br/>            Schreibgeschützt **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/ishape/connection_site_count/) | Gibt die Anzahl der Verbindungspunkte auf der Form zurück.<br/>            Schreibgeschützt **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/ishape/rotation/) | Gibt den Drehwinkel der angegebenen Form um die Z-Achse zurück oder legt ihn fest.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lese-/Schreib **float**. |
| [`x`](/slides/python-net/de/aspose.slides/ishape/x/) | Gibt die X-Koordinate der oberen linken Ecke der Form in Punkten zurück oder legt sie fest.<br/>            Lese-/Schreib **float**. |
| [`y`](/slides/python-net/de/aspose.slides/ishape/y/) | Gibt die Y-Koordinate der oberen linken Ecke der Form in Punkten zurück oder legt sie fest.<br/>            Lese-/Schreib **float**. |
| [`width`](/slides/python-net/de/aspose.slides/ishape/width/) | Gibt die Breite der Form in Punkten zurück oder legt sie fest.<br/>            Lese-/Schreib **float**. |
| [`height`](/slides/python-net/de/aspose.slides/ishape/height/) | Gibt die Höhe der Form in Punkten zurück oder legt sie fest.<br/>            Lese-/Schreib **float**. |
| [`alternative_text`](/slides/python-net/de/aspose.slides/ishape/alternative_text/) | Gibt den alternativen Text zurück oder legt ihn fest, der einer Form zugeordnet ist.<br/>            Lese-/Schreib **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/ishape/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der einer Form zugeordnet ist.<br/>            Lese-/Schreib **str**. |
| [`name`](/slides/python-net/de/aspose.slides/ishape/name/) | Gibt den Namen einer Form zurück oder legt ihn fest.<br/>            Lese-/Schreib **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/ishape/is_decorative/) | Gibt die Option „Als dekorativ markieren“ zurück oder legt sie fest<br/>            Lese-/Schreib **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/ishape/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Schreibgeschützt [`IBaseShapeLock`](/slides/python-net/de/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/de/aspose.slides/ishape/unique_id/) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als permanenter eindeutiger Schlüssel verwendet werden.<br/>            Schreibgeschützt **int**.<br/>            Siehe auch [`IShape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/ishape/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren.<br/>            Schreibgeschützt **int**.<br/>            Siehe auch [`IShape.unique_id`](/slides/python-net/de/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/ishape/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Schreibgeschützt **bool**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/ishape/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeigemodus gerendert wird.<br/>            Lese-/Schreib [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/de/aspose.slides/ishape/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Schreibgeschützt [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/ishape/hyperlink_manager/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/ishape/get_image/#) | Gibt ein Form-Miniaturbild zurück.<br/>            Der Standard-Typ ShapeThumbnailBounds.Shape wird verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Gibt ein Form-Miniaturbild zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/ishape/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/ishape/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/ishape/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/ishape/get_base_placeholder/#) | Gibt eine einfache Platzhalterform zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form ererbt wird).<br/>            Ein None wird zurückgegeben, wenn die aktuelle Form nicht vererbt ist. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)