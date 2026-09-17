---
title: Shape class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shape/
---
## Shape-Klasse

Stellt eine Form auf einer Folie dar.

Der Shape-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/shape/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/shape/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Read-only [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/shape/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Read-only [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/shape/raw_frame/) | Gibt die rohen Frame-Eigenschaften der Form zurück oder setzt sie.<br/>            Read/write [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/shape/frame/) | Gibt die Frame-Eigenschaften der Form zurück oder setzt sie.<br/>            Read/write [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/shape/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Linieneigenschaften besitzen.<br/>            Read-only [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/shape/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/shape/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte auf eine Form anwendet.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen.<br/>            Read-only [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/shape/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Füll-Eigenschaften besitzen.<br/>            Read-only [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/shape/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn.<br/>            Read/write [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/shape/hyperlink_mouse_over/) | Gibt den für Mouseover definierten Hyperlink zurück oder setzt ihn.<br/>            Read/write [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/shape/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/shape/hidden/) | Bestimmt, ob die Form verborgen ist.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/shape/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende der Z-Reihenfolge zurück.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/shape/connection_site_count/) | Gibt die Anzahl der Verbindungsstellen der Form zurück.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/shape/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie.<br/>            Ein positiver Wert bedeutet eine Drehung im Uhrzeigersinn; ein negativer Wert<br/>            bedeutet eine Drehung gegen den Uhrzeigersinn.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/de/aspose.slides/shape/x/) | Liest oder setzt die X-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/de/aspose.slides/shape/y/) | Liest oder setzt die Y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/de/aspose.slides/shape/width/) | Liest oder setzt die Breite der Form, gemessen in Punkten.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/de/aspose.slides/shape/height/) | Liest oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/shape/black_white_mode/) | Die Eigenschaft legt fest, wie eine Form im Schwarz-Weiß-Anzeigemodus dargestellt wird.<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id/) | Gibt einen internen, auf die Präsentation bezogenen Bezeichner zurück, der für Add-Ins oder anderen Code vorgesehen ist.<br/>            Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel behandelt werden.<br/>            Read-only **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id/) | Gibt einen auf die Folie bezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und<br/>            PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren.<br/>            Read-only **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/shape/alternative_text/) | Gibt den alternativen Text zurück, der einer Form zugeordnet ist, oder setzt ihn.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/shape/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück, der einer Form zugeordnet ist, oder setzt ihn.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/de/aspose.slides/shape/name/) | Gibt den Namen einer Form zurück oder setzt ihn.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren Zeichenfolgenwert.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/shape/is_decorative/) | Liest oder setzt die Option 'Als dekorativ markieren'<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/shape/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Read-only [`IBaseShapeLock`](/slides/python-net/de/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/shape/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/shape/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Read-only [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/shape/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Read-only [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/shape/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Read-only [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/shape/get_image/#) | Gibt das Miniaturbild der Form zurück.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | Gibt das Miniaturbild der Form zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/shape/write_as_svg/#iorawiobase) | Speichert den Inhalt der Shape als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Shape als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/shape/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/shape/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/shape/get_base_placeholder/#) | Gibt eine einfache Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folie, von der die aktuelle Form ererbt wird).<br/>            Ein None wird zurückgegeben, wenn die aktuelle Form nicht vererbt ist. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/shape/get_visual_bounds/#) | Liest die visuellen Begrenzungen der Form, berechnet aus ihrem gerenderten Inhalt. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)