---
title: GraphicalObject class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/graphicalobject/
---
## GraphicalObject Klasse

Stellt ein abstraktes grafisches Objekt dar.

**Vererbung:**[`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der GraphicalObject-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/graphicalobject/is_text_holder/) | Bestimmt, ob das Shape ein TextHolder_PPT ist.<br/>            Nur-Lesen **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/graphicalobject/placeholder/) | Gibt den Platzhalter für ein Shape zurück. Gibt None zurück, wenn das Shape keinen Platzhalter hat.<br/>            Nur-Lesen [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/graphicalobject/custom_data/) | Gibt die benutzerdefinierten Daten des Shapes zurück.<br/>            Nur-Lesen [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/graphicalobject/raw_frame/) | Gibt die rohen Frame-Eigenschaften des Shapes zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/graphicalobject/frame/) | Gibt die Frame-Eigenschaften des Shapes zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/graphicalobject/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für ein Shape enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Shape-Typen, die keine Linieneigenschaften haben.<br/>            Nur-Lesen [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/graphicalobject/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für ein Shape enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Shape-Typen, die keine 3D-Eigenschaften haben.<br/>            Nur-Lesen [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/graphicalobject/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf ein Shape angewendet werden.<br/>            Hinweis: kann None zurückgeben für bestimmte Shape-Typen, die keine Effekt-Eigenschaften haben.<br/>            Nur-Lesen [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/graphicalobject/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für ein Shape enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Shape-Typen, die keine Füll-Eigenschaften haben.<br/>            Nur-Lesen [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/graphicalobject/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/graphicalobject/hyperlink_mouse_over/) | Gibt den für Mausüberfahrt definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/graphicalobject/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur-Lesen [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/graphicalobject/hidden/) | Bestimmt, ob das Shape ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/graphicalobject/z_order_position/) | Gibt die Position eines Shapes in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt das Shape am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt das Shape am vorderen Ende der Z-Reihenfolge zurück.<br/>            Nur-Lesen **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/graphicalobject/connection_site_count/) | Gibt die Anzahl der Verbindungsstellen am Shape zurück.<br/>            Nur-Lesen **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/graphicalobject/rotation/) | Gibt die Anzahl der Grad zurück, um die das angegebene Shape um die Z-Achse gedreht ist, oder setzt sie.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert<br/>            bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/graphicalobject/x/) | Liest oder setzt die X-Koordinate der oberen linken Ecke des Shapes, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/graphicalobject/y/) | Liest oder setzt die Y-Koordinate der oberen linken Ecke des Shapes, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/graphicalobject/width/) | Liest oder setzt die Breite des Shapes, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/graphicalobject/height/) | Liest oder setzt die Höhe des Shapes, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/graphicalobject/black_white_mode/) | Eigenschaft gibt an, wie ein Shape im Schwarz-Weiß-Anzeige-Modus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/graphicalobject/unique_id/) | Gibt einen internen, presentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code bestimmt ist.<br/>            Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel behandelt werden.<br/>            Nur-Lesen **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/graphicalobject/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer des Shapes konstant bleibt und<br/>            PowerPoint oder Interop-Code ermöglicht, das Shape zuverlässig von überall im Dokument zu referenzieren.<br/>            Nur-Lesen **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/graphicalobject/alternative_text/) | Gibt den alternativen Text für ein Shape zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/graphicalobject/alternative_text_title/) | Gibt den Titel des alternativen Textes für ein Shape zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/graphicalobject/name/) | Gibt den Namen eines Shapes zurück oder setzt ihn.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren Zeichenkettenwert.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/graphicalobject/is_decorative/) | Liest oder setzt die Option 'Mark as decorative'<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/graphicalobject/shape_lock/) | Gibt die Sperren des Shapes zurück.<br/>            Nur-Lesen [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/graphicalobject/is_grouped/) | Bestimmt, ob das Shape gruppiert ist.<br/>            Nur-Lesen **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/graphicalobject/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn das Shape gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Nur-Lesen [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/graphicalobject/slide/) | Gibt die übergeordnete Folie eines Shapes zurück.<br/>            Nur-Lesen [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/graphicalobject/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur-Lesen [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/de/aspose.slides/graphicalobject/graphical_object_lock/) | Gibt die Sperren des Shapes zurück.<br/>            Nur-Lesen [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/graphicalobject/get_image/#) | Gibt das Shape-Miniaturbild zurück.<br/>            ShapeThumbnailBounds.Shape wird standardmäßig als Typ für die Miniaturbild-Grenzen verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | Gibt das Shape-Miniaturbild zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | Speichert den Inhalt von Shape als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt von Shape als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/graphicalobject/remove_placeholder/#) | Definiert, dass dieses Shape kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/graphicalobject/get_base_placeholder/#) | Gibt ein einfaches Platzhalter-Shape zurück (Shape aus dem Layout und/oder der Master-Folien, von dem das aktuelle Shape erbt).<br/>            Es wird None zurückgegeben, wenn das aktuelle Shape nicht geerbt wurde. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/graphicalobject/get_visual_bounds/#) | Liefert die visuellen Grenzen des Shapes, berechnet aus dessen gerendertem Inhalt. |

### Siehe auch
* Klasse [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)