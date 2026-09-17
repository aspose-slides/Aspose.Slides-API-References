---
title: GroupShape class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/groupshape/
---
## GroupShape Klasse

Stellt eine Gruppe von Shapes auf einer Folie dar.

**Vererbung:**[`GroupShape`](/slides/python-net/de/aspose.slides/groupshape) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der Typ GroupShape stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/groupshape/is_text_holder/) | Bestimmt, ob das Shape ein TextHolder_PPT ist.<br/>            Nur-Lesen **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/groupshape/placeholder/) | Gibt den Platzhalter für ein Shape zurück. Gibt None zurück, wenn das Shape keinen Platzhalter hat.<br/>            Nur-Lesen [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/groupshape/custom_data/) | Gibt die benutzerdefinierten Daten des Shapes zurück.<br/>            Nur-Lesen [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/groupshape/raw_frame/) | Gibt die rohen Eigenschaften des Shape-Frames zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/groupshape/frame/) | Gibt die Eigenschaften des Shape-Frames zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/groupshape/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für ein Shape enthält.<br/>            Hinweis: Gibt None für GroupShape-Objekte zurück, weil sie keine Linieneigenschaften besitzen.<br/>            Nur-Lesen [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/groupshape/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für ein Shape enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Shape-Typen, die keine 3D-Eigenschaften besitzen.<br/>            Nur-Lesen [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/groupshape/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte enthält, die auf ein Shape angewendet werden.<br/>            Hinweis: Kann None zurückgeben für bestimmte Shape-Typen, die keine Effekt-Eigenschaften besitzen.<br/>            Nur-Lesen [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/groupshape/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für ein Shape enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Shape-Typen, die keine Füll-Eigenschaften besitzen.<br/>            Nur-Lesen [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/groupshape/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/groupshape/hyperlink_mouse_over/) | Gibt den für Maus-Over definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/groupshape/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur-Lesen [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/groupshape/hidden/) | Bestimmt, ob das Shape ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/groupshape/z_order_position/) | Gibt die Position eines Shapes in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt das Shape am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt das Shape am vorderen Ende zurück.<br/>            Nur-Lesen **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/groupshape/connection_site_count/) | Gibt die Anzahl der Verbindungspunkte des Shapes zurück.<br/>            Nur-Lesen **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/groupshape/rotation/) | Gibt die Anzahl der Grad zurück, um die das angegebene Shape um die Z-Achse gedreht ist, oder setzt sie.<br/>            Ein positiver Wert steht für eine Drehung im Uhrzeigersinn; ein negativer Wert für eine Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/groupshape/x/) | Gibt die X-Koordinate der oberen linken Ecke des Shapes zurück oder setzt sie, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/groupshape/y/) | Gibt die Y-Koordinate der oberen linken Ecke des Shapes zurück oder setzt sie, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/groupshape/width/) | Gibt die Breite des Shapes zurück oder setzt sie, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/groupshape/height/) | Gibt die Höhe des Shapes zurück oder setzt sie, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/groupshape/black_white_mode/) | Eigenschaft gibt an, wie ein Shape im Schwarz-Weiß-Anzeigemodus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/groupshape/unique_id/) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code bestimmt ist.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel behandelt werden.<br/>            Nur-Lesen **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/groupshape/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer des Shapes konstant bleibt und PowerPoint oder Interop-Code ermöglicht, das Shape zuverlässig von überall im Dokument zu referenzieren.<br/>            Nur-Lesen **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/groupshape/alternative_text/) | Gibt den alternativen Text zurück, der einem Shape zugeordnet ist, oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/groupshape/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück, der einem Shape zugeordnet ist, oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/groupshape/name/) | Gibt den Namen eines Shapes zurück oder setzt ihn.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren String-Wert.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/groupshape/is_decorative/) | Gibt die Option „Als dekorativ markieren“ zurück oder setzt sie.<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/groupshape/shape_lock/) | Gibt die Sperren des Shapes zurück.<br/>            Nur-Lesen [`IGroupShapeLock`](/slides/python-net/de/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/groupshape/is_grouped/) | Bestimmt, ob das Shape gruppiert ist.<br/>            Nur-Lesen **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/groupshape/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn das Shape gruppiert ist. Gibt andernfalls None zurück.<br/>            Nur-Lesen [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/groupshape/slide/) | Gibt die übergeordnete Folie des Shapes zurück.<br/>            Nur-Lesen [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/groupshape/presentation/) | Gibt die übergeordnete Präsentation der Folie zurück.<br/>            Nur-Lesen [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/de/aspose.slides/groupshape/group_shape_lock/) | Gibt die Sperren des Shapes zurück.<br/>            Nur-Lesen [`IGroupShapeLock`](/slides/python-net/de/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/de/aspose.slides/groupshape/shapes/) | Gibt die Sammlung der Shapes innerhalb der Gruppe zurück.<br/>            Nur-Lesen [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection). |

## Methoden

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/groupshape/get_image/#) | Gibt das Shape-Thumbnail zurück.<br/>            Der Standard-Typ ShapeThumbnailBounds.Shape wird verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | Gibt das Shape-Thumbnail zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Speichert den Inhalt des Shapes als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt des Shapes als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/groupshape/remove_placeholder/#) | Definiert, dass dieses Shape kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/groupshape/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/groupshape/get_base_placeholder/#) | Gibt ein Basis-Platzhalter-Shape zurück (ein Shape aus dem Layout- und/oder Master-Slide, von dem das aktuelle Shape erbt).<br/>            Gibt None zurück, wenn das aktuelle Shape nicht geerbt ist. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/groupshape/get_visual_bounds/#) | Ermittelt die visuellen Grenzen des Shapes, berechnet aus seinem gerenderten Inhalt. |


### Siehe auch
* class [`GroupShape`](/slides/python-net/de/aspose.slides/groupshape)
* class [`Shape`](/slides/python-net/de/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)