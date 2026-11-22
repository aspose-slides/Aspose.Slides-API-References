---
title: VideoFrame class
second_title: Aspose.Slides für Python über .NET API Referenz
description: 
type: docs
url: /de/aspose.slides/videoframe/
---
## VideoFrame Klasse

Stellt einen Videoclip auf einer Folie dar.

**Vererbung:**[`VideoFrame`](/slides/python-net/de/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/de/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der VideoFrame-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/videoframe/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur lesbar **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/videoframe/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur lesbar [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/videoframe/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/videoframe/raw_frame/) | Gibt die Roh-Formrahmen-Eigenschaften zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/videoframe/frame/) | Gibt die Formrahmen-Eigenschaften zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/videoframe/line_format/) | Gibt das LineFormat-Objekt zurück, das Linieneigenschafts-Formate für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formen, die keine Linieneigenschaften besitzen.<br/>            Nur lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/videoframe/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formen, die keine 3D-Eigenschaften besitzen.<br/>            Nur lesbar [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/videoframe/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden.<br/>            Hinweis: kann None zurückgeben für bestimmte Formen, die keine Effekt-Eigenschaften besitzen.<br/>            Nur lesbar [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/videoframe/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformat-Eigenschaften für eine Form enthält.<br/>            Hinweis: kann None zurückgeben für bestimmte Formen, die keine Füllegeigenschaften besitzen.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/videoframe/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/videoframe/hyperlink_mouse_over/) | Gibt den für Mauszeiger-Überlagerung definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/videoframe/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur lesbar [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/videoframe/hidden/) | Bestimmt, ob die Form verborgen ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/videoframe/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende der Z-Reihenfolge zurück.<br/>            Nur lesbar **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/videoframe/connection_site_count/) | Gibt die Anzahl der Anschlusspunkte an der Form zurück.<br/>            Nur lesbar **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/videoframe/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert<br/>            bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/videoframe/x/) | Liest oder setzt die X-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/videoframe/y/) | Liest oder setzt die Y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/videoframe/width/) | Liest oder setzt die Breite der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/videoframe/height/) | Liest oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/videoframe/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeigemodus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/videoframe/unique_id/) | Gibt einen internen, presentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code bestimmt ist.<br/>            Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel behandelt werden.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/videoframe/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren.<br/>            Nur lesbar **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/videoframe/alternative_text/) | Gibt den alternativen Text zurück, der mit einer Form verbunden ist, oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/videoframe/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück, der mit einer Form verbunden ist, oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/videoframe/name/) | Gibt den Namen einer Form zurück oder setzt ihn.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren Zeichenfolgenwert.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/videoframe/is_decorative/) | Liest oder setzt die Option 'Als dekorativ markieren'<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/videoframe/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IPictureFrameLock`](/slides/python-net/de/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/videoframe/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur lesbar **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/videoframe/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls gibt es None zurück.<br/>            Nur lesbar [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/videoframe/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Nur lesbar [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/videoframe/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/de/aspose.slides/videoframe/shape_style/) | Gibt das Stil-Objekt der Form zurück.<br/>            Nur lesbar [`IShapeStyle`](/slides/python-net/de/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/de/aspose.slides/videoframe/shape_type/) | Gibt den AutoShape-Typ für ein PictureFrame zurück oder setzt ihn.<br/>            Es sind alle Elemente der Menge [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) zulässig, <br/>            außer allen Arten von Linien:<br/>    ShapeType.Line,<br/>    ShapeType.StraightConnector1,<br/>    ShapeType.BentConnector2,<br/>    ShapeType.BentConnector3,<br/>    ShapeType.BentConnector4,<br/>    ShapeType.BentConnector5,<br/>    ShapeType.CurvedConnector2,<br/>    ShapeType.CurvedConnector3,<br/>    ShapeType.CurvedConnector4,<br/>    ShapeType.CurvedConnector5.<br/>            Lesen/Schreiben [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/de/aspose.slides/videoframe/adjustments/) | Gibt eine Sammlung von Anpassungswerten der Form zurück.<br/>            Nur lesbar [`IAdjustValueCollection`](/slides/python-net/de/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/de/aspose.slides/videoframe/picture_frame_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesbar [`IPictureFrameLock`](/slides/python-net/de/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/de/aspose.slides/videoframe/picture_format/) | Gibt das PictureFillFormat-Objekt für einen Bildrahmen zurück.<br/>            Nur lesbar [`IPictureFillFormat`](/slides/python-net/de/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/de/aspose.slides/videoframe/relative_scale_height/) | Gibt den Höhen-Skalierungsfaktor (relativ zur Originalbildgröße) des Bildrahmens zurück oder setzt ihn. Der Wert 1.0 entspricht 100%.<br/>            Lesen/Schreiben **float**. |
| [`relative_scale_width`](/slides/python-net/de/aspose.slides/videoframe/relative_scale_width/) | Gibt den Breiten-Skalierungsfaktor (relativ zur Originalbildgröße) des Bildrahmens zurück oder setzt ihn. Der Wert 1.0 entspricht 100%.<br/>            Lesen/Schreiben **float**. |
| [`is_cameo`](/slides/python-net/de/aspose.slides/videoframe/is_cameo/) | Bestimmt, ob das PictureFrame ein Cameo-Objekt ist oder nicht.<br/>            Nur lesbar **bool**. |
| [`rewind_video`](/slides/python-net/de/aspose.slides/videoframe/rewind_video/) | Bestimmt, ob ein Video automatisch zum Start zurückgespult wird<br/>            sobald das Video die Wiedergabe beendet hat.<br/>            Lesen/Schreiben **bool**. |
| [`play_loop_mode`](/slides/python-net/de/aspose.slides/videoframe/play_loop_mode/) | Bestimmt, ob ein Video wiederholt wird.<br/>            Lesen/Schreiben **bool**. |
| [`hide_at_showing`](/slides/python-net/de/aspose.slides/videoframe/hide_at_showing/) | Bestimmt, ob ein VideoFrame verborgen ist.<br/>            Lesen/Schreiben **bool**. |
| [`volume`](/slides/python-net/de/aspose.slides/videoframe/volume/) | Gibt die Audio-Lautstärke zurück oder setzt sie.<br/>            Lesen/Schreiben [`AudioVolumeMode`](/slides/python-net/de/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/de/aspose.slides/videoframe/volume_value/) | Gibt die exakte Video-Lautstärke als Prozentsatz zurück oder setzt sie.<br/>             Der Wert wird als Prozentsatz von 0 bis 100 ausgedrückt. Verwenden Sie diese Eigenschaft,<br/>             um Lautstärkewerte zu lesen oder zu setzen, die genauer sind als die vordefinierten<br/>             Werte, die über die [`VideoFrame.volume`](/slides/python-net/de/aspose.slides/videoframe/volume)-Eigenschaft verfügbar sind.<br/>             Lesen/Schreiben **float**. |
| [`play_mode`](/slides/python-net/de/aspose.slides/videoframe/play_mode/) | Gibt den Videowiedergabemodus zurück oder setzt ihn.<br/>            Lesen/Schreiben [`VideoPlayModePreset`](/slides/python-net/de/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/de/aspose.slides/videoframe/full_screen_mode/) | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird.<br/>            Lesen/Schreiben **bool**. |
| [`link_path_long`](/slides/python-net/de/aspose.slides/videoframe/link_path_long/) | Gibt den Namen einer Videodatei zurück, die mit einem VideoFrame verknüpft ist, oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`embedded_video`](/slides/python-net/de/aspose.slides/videoframe/embedded_video/) | Gibt das eingebettete Video-Objekt zurück oder setzt es.<br/>            Lesen/Schreiben [`IVideo`](/slides/python-net/de/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/de/aspose.slides/videoframe/trim_from_start/) | Trim-Start [ms] |
| [`trim_from_end`](/slides/python-net/de/aspose.slides/videoframe/trim_from_end/) | Trim-Ende [ms] |
| [`caption_tracks`](/slides/python-net/de/aspose.slides/videoframe/caption_tracks/) | Gibt die Sammlung von Untertiteln zurück, die dem Video-Frame zugeordnet sind.<br/>             Diese Eigenschaft ist nur lesbar und gibt ein [`ICaptionsCollection`](/slides/python-net/de/aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/videoframe/get_image/#) | Gibt das Vorschaubild der Form zurück.<br/>            Der Standard-Typ für die Form-Vorschaubild-Grenzen ist ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Gibt das Vorschaubild der Form zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/videoframe/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/videoframe/get_base_placeholder/#) | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form ererbt wird).<br/>            Wird None zurückgegeben, falls die aktuelle Form nicht geerbt wird. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/videoframe/get_visual_bounds/#) | Liest die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [`get_geometry_paths(self)`](/slides/python-net/de/aspose.slides/videoframe/get_geometry_paths/#) | Gibt die Kopie des Pfads der geometrischen Form zurück. Die Koordinaten sind relativ zur linken oberen Ecke der Form. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/de/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Aktualisiert die Geometrie der Form aus dem [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)-Objekt. Koordinaten müssen relativ zur linken<br/>             oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/de/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Aktualisiert die Geometrie der Form aus einem Array von [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath). Koordinaten müssen relativ zur linken<br/>             oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/de/aspose.slides/videoframe/create_shape_elements/#) | Erstellt und gibt ein Array der Form-Elemente zurück. |

### Siehe auch
* Klasse [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape)
* Klasse [`PictureFrame`](/slides/python-net/de/aspose.slides/pictureframe)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Klasse [`VideoFrame`](/slides/python-net/de/aspose.slides/videoframe)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)