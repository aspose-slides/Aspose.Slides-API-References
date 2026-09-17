---
title: OleObjectFrame class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/oleobjectframe/
---
## OleObjectFrame Klasse

Stellt ein OLE-Objekt auf einer Folie dar.

**Vererbung:**[`OleObjectFrame`](/slides/python-net/de/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der OleObjectFrame-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/oleobjectframe/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur-Lesen **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/oleobjectframe/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur-Lesen [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/oleobjectframe/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur-Lesen [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/oleobjectframe/raw_frame/) | Gibt die rohen Eigenschaften des Formrahmens zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/oleobjectframe/frame/) | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/oleobjectframe/line_format/) | Gibt das LineFormat-Objekt zurück, das Linieneigenschaften für eine Form enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine Linieneigenschaften besitzen.<br/>            Nur-Lesen [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/oleobjectframe/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen.<br/>            Nur-Lesen [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/oleobjectframe/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte auf eine Form anwendet.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen.<br/>            Nur-Lesen [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/oleobjectframe/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine Füllungseigenschaften besitzen.<br/>            Nur-Lesen [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/oleobjectframe/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Gibt den für Mausüberfahren definierten Hyperlink zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/oleobjectframe/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur-Lesen [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/oleobjectframe/hidden/) | Bestimmt, ob die Form verborgen ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/oleobjectframe/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form ganz hinten in der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form ganz vorne in der Z-Reihenfolge zurück.<br/>            Nur-Lesen **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/oleobjectframe/connection_site_count/) | Gibt die Anzahl der Verbindungspunkte an der Form zurück.<br/>            Nur-Lesen **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/oleobjectframe/rotation/) | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die Z-Achse gedreht ist.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/oleobjectframe/x/) | Liest oder setzt die X-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/oleobjectframe/y/) | Liest oder setzt die Y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/oleobjectframe/width/) | Liest oder setzt die Breite der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/oleobjectframe/height/) | Liest oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/oleobjectframe/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/oleobjectframe/unique_id/) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als dauerhafter eindeutiger Schlüssel behandelt werden.<br/>            Nur-Lesen **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/oleobjectframe/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, zuverlässig von überall im Dokument auf die Form zu verweisen.<br/>            Nur-Lesen **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/oleobjectframe/alternative_text/) | Gibt den alternativen Text zurück oder legt ihn fest, der einer Form zugeordnet ist.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/oleobjectframe/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der einer Form zugeordnet ist.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/oleobjectframe/name/) | Gibt den Namen einer Form zurück oder legt ihn fest.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren Zeichenfolgenwert.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/oleobjectframe/is_decorative/) | Liest oder setzt die Option 'Als dekorativ markieren'<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/oleobjectframe/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur-Lesen [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/oleobjectframe/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur-Lesen **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/oleobjectframe/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Nur-Lesen [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/oleobjectframe/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Nur-Lesen [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/oleobjectframe/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur-Lesen [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/de/aspose.slides/oleobjectframe/graphical_object_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur-Lesen [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/de/aspose.slides/oleobjectframe/substitute_picture_format/) | Gibt das OleObject-Bildfüllungs-Eigenschaftsobjekt zurück.<br/>            Nur-Lesen [`IPictureFillFormat`](/slides/python-net/de/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/de/aspose.slides/oleobjectframe/substitute_picture_title/) | Gibt den Titel für das OleObject-Symbol zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`object_name`](/slides/python-net/de/aspose.slides/oleobjectframe/object_name/) | Gibt den Namen eines Objekts zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`object_prog_id`](/slides/python-net/de/aspose.slides/oleobjectframe/object_prog_id/) | Gibt die ProgID eines Objekts zurück.<br/>            Nur-Lesen **str**. |
| [`link_file_name`](/slides/python-net/de/aspose.slides/oleobjectframe/link_file_name/) | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. Der Kurzdateiname wird verwendet.<br/>            Nur-Lesen **str**. |
| [`link_path_long`](/slides/python-net/de/aspose.slides/oleobjectframe/link_path_long/) | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. Der Langdateiname wird verwendet.<br/>            Lesen/Schreiben **str**. |
| [`link_path_relative`](/slides/python-net/de/aspose.slides/oleobjectframe/link_path_relative/) | Gibt den relativen Pfad zu einer verknüpften Datei zurück, falls vorhanden, sonst wird eine leere Zeichenfolge zurückgegeben.<br/>            Nur-Lesen **str**. |
| [`embedded_file_label`](/slides/python-net/de/aspose.slides/oleobjectframe/embedded_file_label/) | Gibt den Dateinamen des eingebetteten OLE-Objekts zurück |
| [`embedded_file_name`](/slides/python-net/de/aspose.slides/oleobjectframe/embedded_file_name/) | Gibt den Pfad des eingebetteten OLE-Objekts zurück |
| [`embedded_data`](/slides/python-net/de/aspose.slides/oleobjectframe/embedded_data/) | Liest oder setzt Informationen über eingebettete OLE-Daten.<br/>            Lesen/Schreiben [`IOleEmbeddedDataInfo`](/slides/python-net/de/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/de/aspose.slides/oleobjectframe/is_object_icon/) | Bestimmt, ob ein Objekt als Symbol sichtbar ist.<br/>            Lesen/Schreiben **bool**. |
| [`is_object_link`](/slides/python-net/de/aspose.slides/oleobjectframe/is_object_link/) | Bestimmt, ob ein Objekt mit einer externen Datei verknüpft ist.<br/>            Nur-Lesen **bool**. |
| [`update_automatic`](/slides/python-net/de/aspose.slides/oleobjectframe/update_automatic/) | Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird.<br/>            Lesen/Schreiben **bool**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/oleobjectframe/get_image/#) | Gibt das Form-Thumbnail zurück.<br/>            Der Typ ShapeThumbnailBounds.Shape für Thumbnail-Grenzen wird standardmäßig verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Gibt das Form-Thumbnail zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/oleobjectframe/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/oleobjectframe/get_base_placeholder/#) | Gibt eine einfache Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form ererbt wird).<br/>            Es wird None zurückgegeben, wenn die aktuelle Form nicht vererbt ist. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/oleobjectframe/get_visual_bounds/#) | Liest die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/de/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Setzt Informationen über eingebettete OLE-Daten.<br/>            <br/>            Diese Methode ändert die Eigenschaften des Objekts, um die neuen Daten widerzuspiegeln und <br/>            setzt das IsObjectLink-Flag auf false, was anzeigt, dass das OLE-Objekt eingebettet ist. |

### Siehe auch
* Klasse [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject)
* Klasse [`OleObjectFrame`](/slides/python-net/de/aspose.slides/oleobjectframe)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)