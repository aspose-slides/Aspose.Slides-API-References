---
title: InkActions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ink/inkactions/
---
## InkActions Klasse

Stellt die Wurzel der Ink-Aktionen dar.

**Vererbung:**[`InkActions`](/slides/python-net/de/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der InkActions-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides.ink/inkactions/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Schreibgeschützt **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides.ink/inkactions/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Schreibgeschützt [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides.ink/inkactions/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Schreibgeschützt [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides.ink/inkactions/raw_frame/) | Gibt die rohen Form-Rahmen-Eigenschaften zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides.ink/inkactions/frame/) | Gibt die Form-Rahmen-Eigenschaften zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides.ink/inkactions/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Linieneigenschaften besitzen.<br/>            Schreibgeschützt [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides.ink/inkactions/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen.<br/>            Schreibgeschützt [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides.ink/inkactions/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet werden.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen.<br/>            Schreibgeschützt [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides.ink/inkactions/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formtypen, die keine Fülleigenschaften besitzen.<br/>            Schreibgeschützt [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides.ink/inkactions/hyperlink_click/) | Gibt den für einen Mausklick definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | Gibt den für ein Mouse-Over definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides.ink/inkactions/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Schreibgeschützt [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides.ink/inkactions/hidden/) | Bestimmt, ob die Form ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides.ink/inkactions/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende der Z-Reihenfolge zurück.<br/>            Schreibgeschützt **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides.ink/inkactions/connection_site_count/) | Gibt die Anzahl der Verbindungsstellen an der Form zurück.<br/>            Schreibgeschützt **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides.ink/inkactions/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehen im Uhrzeigersinn; ein negativer Wert bedeutet Drehen gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides.ink/inkactions/x/) | Gibt die X-Koordinate der linken oberen Ecke der Form zurück oder setzt sie, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides.ink/inkactions/y/) | Gibt die Y-Koordinate der linken oberen Ecke der Form zurück oder setzt sie, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides.ink/inkactions/width/) | Gibt die Breite der Form zurück oder setzt sie, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides.ink/inkactions/height/) | Gibt die Höhe der Form zurück oder setzt sie, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides.ink/inkactions/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeige-Modus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides.ink/inkactions/unique_id/) | Gibt einen internen, präsenz-bezogenen Bezeichner zurück, der für Add-ins oder anderen Code gedacht ist.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als persistent eindeutiger Schlüssel behandelt werden.<br/>            Schreibgeschützt **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides.ink/inkactions/office_interop_shape_id/) | Gibt einen folien-bezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument aus zu referenzieren.<br/>            Schreibgeschützt **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides.ink/inkactions/alternative_text/) | Gibt den alternativen Text, der mit einer Form verknüpft ist, zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides.ink/inkactions/alternative_text_title/) | Gibt den Titel des alternativen Textes, der mit einer Form verknüpft ist, zurück oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides.ink/inkactions/name/) | Gibt den Namen einer Form zurück oder setzt ihn.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren Zeichenkettenwert.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides.ink/inkactions/is_decorative/) | Gibt die Option 'Als dekorativ kennzeichnen' zurück oder setzt sie<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides.ink/inkactions/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Schreibgeschützt [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides.ink/inkactions/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Schreibgeschützt **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides.ink/inkactions/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Schreibgeschützt [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides.ink/inkactions/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Schreibgeschützt [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides.ink/inkactions/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Schreibgeschützt [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/de/aspose.slides.ink/inkactions/graphical_object_lock/) | Gibt die Sperren der Form zurück.<br/>            Schreibgeschützt [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides.ink/inkactions/get_image/#) | Gibt das Form-Vorschaubild zurück.<br/>            ShapeThumbnailBounds.Shape Form-Vorschaubild-Grenztyp wird standardmäßig verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | Gibt das Form-Vorschaubild zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides.ink/inkactions/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides.ink/inkactions/get_base_placeholder/#) | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt).<br/>            None wird zurückgegeben, wenn die aktuelle Form nicht vererbt wird. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides.ink/inkactions/get_visual_bounds/#) | Ermittelt die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |

### Siehe auch
* Klasse [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject)
* Klasse [`InkActions`](/slides/python-net/de/aspose.slides.ink/inkactions)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Modul [`aspose.slides.ink`](/slides/python-net/de/aspose.slides.ink)
* Bibliothek [`Aspose.Slides`](/slides/python-net)