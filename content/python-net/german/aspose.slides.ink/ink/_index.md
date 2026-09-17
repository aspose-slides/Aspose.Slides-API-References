---
title: Ink class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ink/ink/
---
## Ink Klasse

Represents an Ink object on a slide.

**Vererbung:**[`Ink`](/slides/python-net/de/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

The Ink type exposes the following members:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides.ink/ink/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Schreibgeschützt **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides.ink/ink/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Schreibgeschützt [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides.ink/ink/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Schreibgeschützt [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides.ink/ink/raw_frame/) | Gibt die Roh-Formrahmen-Eigenschaften zurück oder setzt sie.<br/>            Lese/Schreib [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides.ink/ink/frame/) | Gibt die Formrahmen-Eigenschaften zurück oder setzt sie.<br/>            Lese/Schreib [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides.ink/ink/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann für bestimmte Formtypen, die keine Linieneigenschaften besitzen, None zurückgeben.<br/>            Schreibgeschützt [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides.ink/ink/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: kann für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen, None zurückgeben.<br/>            Schreibgeschützt [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides.ink/ink/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte, die auf eine Form angewendet werden, enthält.<br/>            Hinweis: kann für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen, None zurückgeben.<br/>            Schreibgeschützt [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides.ink/ink/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann für bestimmte Formtypen, die keine Fülleigenschaften besitzen, None zurückgeben.<br/>            Schreibgeschützt [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides.ink/ink/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn.<br/>            Lese/Schreib [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides.ink/ink/hyperlink_mouse_over/) | Gibt den für Maus-over definierten Hyperlink zurück oder setzt ihn.<br/>            Lese/Schreib [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides.ink/ink/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Schreibgeschützt [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides.ink/ink/hidden/) | Bestimmt, ob die Form ausgeblendet ist.<br/>            Lese/Schreib **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides.ink/ink/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende der Z-Reihenfolge zurück.<br/>            Schreibgeschützt **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides.ink/ink/connection_site_count/) | Gibt die Anzahl der Verbindungspunkte der Form zurück.<br/>            Schreibgeschützt **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides.ink/ink/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert<br/>            bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lese/Schreib **float**. |
| [`x`](/slides/python-net/de/aspose.slides.ink/ink/x/) | Liest oder setzt die X-Koordinate der linken oberen Ecke der Form, gemessen in Punkten.<br/>            Lese/Schreib **float**. |
| [`y`](/slides/python-net/de/aspose.slides.ink/ink/y/) | Liest oder setzt die Y-Koordinate der linken oberen Ecke der Form, gemessen in Punkten.<br/>            Lese/Schreib **float**. |
| [`width`](/slides/python-net/de/aspose.slides.ink/ink/width/) | Liest oder setzt die Breite der Form, gemessen in Punkten.<br/>            Lese/Schreib **float**. |
| [`height`](/slides/python-net/de/aspose.slides.ink/ink/height/) | Liest oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Lese/Schreib **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides.ink/ink/black_white_mode/) | Die Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeige-Modus gerendert wird.<br/>            Lese/Schreib [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides.ink/ink/unique_id/) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für die Verwendung durch Add-Ins oder anderen Code bestimmt ist.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als beständiger eindeutiger Schlüssel behandelt werden.<br/>            Schreibgeschützt **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides.ink/ink/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und<br/>            PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren.<br/>            Schreibgeschützt **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides.ink/ink/alternative_text/) | Gibt den alternativen Text zurück, der mit einer Form verknüpft ist, oder setzt ihn.<br/>            Lese/Schreib **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides.ink/ink/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück, der mit einer Form verknüpft ist, oder setzt ihn.<br/>            Lese/Schreib **str**. |
| [`name`](/slides/python-net/de/aspose.slides.ink/ink/name/) | Gibt den Namen einer Form zurück oder setzt ihn.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren Zeichenfolgenwert.<br/>            Lese/Schreib **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides.ink/ink/is_decorative/) | Liest oder setzt die Option 'Als dekorativ markieren'<br/>            Lese/Schreib **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides.ink/ink/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Schreibgeschützt [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides.ink/ink/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Schreibgeschützt **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides.ink/ink/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Schreibgeschützt [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides.ink/ink/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Schreibgeschützt [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides.ink/ink/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Schreibgeschützt [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/de/aspose.slides.ink/ink/graphical_object_lock/) | Gibt die Sperren der Form zurück.<br/>            Schreibgeschützt [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/de/aspose.slides.ink/ink/traces/) | Liest alle Spuren, die im IInk-Element [`IInkTrace`](/slides/python-net/de/aspose.slides.ink/iinktrace) enthalten sind.<br/>            Schreibgeschützt. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides.ink/ink/get_image/#) | Gibt das Form-Vorschaubild zurück.<br/>            Der Standard-Typ ShapeThumbnailBounds.Shape wird für die Form-Vorschaubild-Grenzen verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Gibt das Form-Vorschaubild zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides.ink/ink/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides.ink/ink/get_base_placeholder/#) | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folie, von der die aktuelle Form ererbt wird).<br/>            Wenn die aktuelle Form nicht ererbt wurde, wird None zurückgegeben. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides.ink/ink/get_visual_bounds/#) | Ermittelt die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/de/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Registriert ein Bild in der Sammlung benutzerdefinierter Bilder, die zur Simulation visueller Effekte für Ink-Pinsel verwendet werden.<br/>            Diese Bilder werden beim Rendern von Ink mit bestimmten [`InkEffectType`](/slides/python-net/de/aspose.slides.ink/inkeffecttype)-Werten verwendet,<br/>            wie Galaxy, Rainbow usw. Durch das Bereitstellen eigener Bilder können Sie steuern, wie jeder Ink-Effekt aussieht. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/de/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Entfernt die Registrierung eines Bildes aus der Sammlung benutzerdefinierter Bilder, die zur Simulation visueller Effekte für Ink-Pinsel verwendet werden<br/>            zuvor registrierte Bilder über **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### Siehe Auch
* Klasse [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject)
* Klasse [`Ink`](/slides/python-net/de/aspose.slides.ink/ink)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Modul [`aspose.slides.ink`](/slides/python-net/de/aspose.slides.ink)
* Bibliothek [`Aspose.Slides`](/slides/python-net)