---
title: SummaryZoomFrame class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame Klasse

Stellt ein Summary Zoom-Objekt in einer Folie dar.

**Vererbung:**[`SummaryZoomFrame`](/slides/python-net/de/aspose.slides/summaryzoomframe) → [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der Typ SummaryZoomFrame stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/summaryzoomframe/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur-Lesen **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/summaryzoomframe/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur-Lesen [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/summaryzoomframe/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur-Lesen [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/summaryzoomframe/raw_frame/) | Gibt die Roh-Formrahmen-Eigenschaften zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/summaryzoomframe/frame/) | Gibt die Formrahmen-Eigenschaften zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/summaryzoomframe/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Linieneigenschaften besitzen, None zurückgeben.<br/>            Nur-Lesen [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/summaryzoomframe/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3-D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine 3-D-Eigenschaften besitzen, None zurückgeben.<br/>            Nur-Lesen [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/summaryzoomframe/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte, die auf eine Form angewendet werden, enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen, None zurückgeben.<br/>            Nur-Lesen [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/summaryzoomframe/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Füll-Eigenschaften besitzen, None zurückgeben.<br/>            Nur-Lesen [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/summaryzoomframe/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/summaryzoomframe/hyperlink_mouse_over/) | Gibt den für Maus-Over definierten Hyperlink zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/summaryzoomframe/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur-Lesen [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/summaryzoomframe/hidden/) | Bestimmt, ob die Form ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/summaryzoomframe/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende der Z-Reihenfolge zurück.<br/>            Nur-Lesen **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/summaryzoomframe/connection_site_count/) | Gibt die Anzahl der Verbindungsstellen an der Form zurück.<br/>            Nur-Lesen **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/summaryzoomframe/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist,<br/>            oder legt sie fest. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert<br/>            bedeutet Drehung entgegen dem Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/summaryzoomframe/x/) | Liefert oder setzt die X-Koordinate der linken oberen Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/summaryzoomframe/y/) | Liefert oder setzt die Y-Koordinate der linken oberen Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/summaryzoomframe/width/) | Liefert oder setzt die Breite der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/summaryzoomframe/height/) | Liefert oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/summaryzoomframe/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-und-Weiß-Anzeigemodus dargestellt wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/summaryzoomframe/unique_id/) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist.<br/>            Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als ein persistenter eindeutiger Schlüssel behandelt werden.<br/>            Nur-Lesen **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/summaryzoomframe/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und<br/>            PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren.<br/>            Nur-Lesen **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/summaryzoomframe/alternative_text/) | Gibt den alternativen Text zurück, der einer Form zugeordnet ist, oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/summaryzoomframe/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück, der einer Form zugeordnet ist, oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/summaryzoomframe/name/) | Gibt den Namen einer Form zurück oder legt ihn fest.<br/>            Darf nicht None sein. Leere Zeichenkette verwenden, falls nötig.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/summaryzoomframe/is_decorative/) | Liefert oder setzt die Option 'Mark as decorative'<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/summaryzoomframe/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur-Lesen [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/summaryzoomframe/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur-Lesen **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/summaryzoomframe/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Nur-Lesen [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/summaryzoomframe/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Nur-Lesen [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/summaryzoomframe/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur-Lesen [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/de/aspose.slides/summaryzoomframe/graphical_object_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur-Lesen [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`layout`](/slides/python-net/de/aspose.slides/summaryzoomframe/layout/) | Liefert das Layout der Summary-Zoom-Abschnitte im Rahmen.<br/>            Standardwert ist GridLayout. |
| [`summary_zoom_collection`](/slides/python-net/de/aspose.slides/summaryzoomframe/summary_zoom_collection/) | Liefert [`ISummaryZoomSectionCollection`](/slides/python-net/de/aspose.slides/isummaryzoomsectioncollection) für das Summary-Zoom-Frame-Objekt. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/summaryzoomframe/get_image/#) | Gibt das Form-Vorschaubild zurück.<br/>            ShapeThumbnailBounds.Shape-Vorschaubild-Grenztyp wird standardmäßig verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/summaryzoomframe/get_image/#shapethumbnailbounds-float-float) | Gibt das Form-Vorschaubild zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/summaryzoomframe/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/summaryzoomframe/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/summaryzoomframe/get_base_placeholder/#) | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form ererbt wird).<br/>            Wird None zurückgegeben, wenn die aktuelle Form nicht vererbt ist. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/summaryzoomframe/get_visual_bounds/#) | Liefert die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |

### Siehe auch
* Klasse [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Klasse [`SummaryZoomFrame`](/slides/python-net/de/aspose.slides/summaryzoomframe)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)