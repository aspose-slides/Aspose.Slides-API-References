---
title: VideoFrame class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/videoframe/
---
## VideoFrame-Klasse

Stellt einen Videoclip auf einer Folie dar.

**Inheritance:**[`VideoFrame`](/slides/python-net/de/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/de/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der Typ VideoFrame stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/videoframe/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur-lesbar **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/videoframe/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur-lesbar [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/videoframe/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur-lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/videoframe/raw_frame/) | Gibt die rohen Eigenschaften des Formrahmens zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/videoframe/frame/) | Gibt die Eigenschaften des Formrahmens zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/videoframe/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Linieneigenschaften haben, None zurückgeben.<br/>            Nur-lesbar [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/videoframe/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine 3D-Eigenschaften haben, None zurückgeben.<br/>            Nur-lesbar [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/videoframe/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Effekt-Eigenschaften haben, None zurückgeben.<br/>            Nur-lesbar [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/videoframe/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formtypen, die keine Füll-Eigenschaften haben, None zurückgeben.<br/>            Nur-lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/videoframe/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/videoframe/hyperlink_mouse_over/) | Gibt den für Maus-over definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/videoframe/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur-lesbar [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/videoframe/hidden/) | Bestimmt, ob die Form ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/videoframe/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form ganz hinten in der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form ganz vorne zurück.<br/>            Nur-lesbar **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/videoframe/connection_site_count/) | Gibt die Anzahl der Anschlusspunkte auf der Form zurück.<br/>            Nur-lesbar **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/videoframe/rotation/) | Gibt die Drehung der angegebenen Form um die Z-Achse in Grad zurück oder setzt sie.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/videoframe/x/) | Liest oder setzt die x-Koordinate der linken oberen Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/videoframe/y/) | Liest oder setzt die y-Koordinate der linken oberen Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/videoframe/width/) | Liest oder setzt die Breite der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/videoframe/height/) | Liest oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/videoframe/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeigemodus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/videoframe/unique_id/) | Gibt einen internen, an die Präsentation gebundenen Bezeichner zurück, der von Add-Ins oder anderem Code verwendet werden soll.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als dauerhafter eindeutiger Schlüssel behandelt werden.<br/>            Nur-lesbar **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/videoframe/office_interop_shape_id/) | Gibt einen an die Folie gebundenen eindeutigen Bezeichner zurück, der für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form von überall im Dokument zuverlässig zu referenzieren.<br/>            Nur-lesbar **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/videoframe/alternative_text/) | Gibt den alternativen Text zurück, der mit einer Form verknüpft ist, oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/videoframe/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück, der mit einer Form verknüpft ist, oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/videoframe/name/) | Gibt den Namen einer Form zurück oder setzt ihn.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren Zeichenkettenwert.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/videoframe/is_decorative/) | Liest oder setzt die Option 'Als dekorativ markieren'<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/videoframe/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur-lesbar [`IPictureFrameLock`](/slides/python-net/de/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/videoframe/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur-lesbar **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/videoframe/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Nur-lesbar [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/videoframe/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Nur-lesbar [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/videoframe/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur-lesbar [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/de/aspose.slides/videoframe/shape_style/) | Gibt das Stilobjekt der Form zurück.<br/>            Nur-lesbar [`IShapeStyle`](/slides/python-net/de/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/de/aspose.slides/videoframe/shape_type/) | Gibt den AutoShape-Typ für einen PictureFrame zurück oder setzt ihn.<br/>            Es sind alle Elemente des Satzes [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) zulässig, <br/>            außer allen Arten von Linien:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lesen/Schreiben [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/de/aspose.slides/videoframe/adjustments/) | Gibt eine Sammlung von Anpassungswerten der Form zurück.<br/>            Nur-lesbar [`IAdjustValueCollection`](/slides/python-net/de/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/de/aspose.slides/videoframe/picture_frame_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur-lesbar [`IPictureFrameLock`](/slides/python-net/de/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/de/aspose.slides/videoframe/picture_format/) | Gibt das PictureFillFormat-Objekt für einen Bildrahmen zurück.<br/>            Nur-lesbar [`IPictureFillFormat`](/slides/python-net/de/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/de/aspose.slides/videoframe/relative_scale_height/) | Gibt den Skalierungsfaktor für die Höhe (relativ zur Originalbildgröße) des Bildrahmens zurück oder setzt ihn. Der Wert 1.0 entspricht 100%.<br/>            Lesen/Schreiben **float**. |
| [`relative_scale_width`](/slides/python-net/de/aspose.slides/videoframe/relative_scale_width/) | Gibt den Skalierungsfaktor für die Breite (relativ zur Originalbildgröße) des Bildrahmens zurück oder setzt ihn. Der Wert 1.0 entspricht 100%.<br/>            Lesen/Schreiben **float**. |
| [`is_cameo`](/slides/python-net/de/aspose.slides/videoframe/is_cameo/) | Bestimmt, ob der PictureFrame ein Cameo-Objekt ist oder nicht.<br/>            Nur-lesbar **bool**. |
| [`rewind_video`](/slides/python-net/de/aspose.slides/videoframe/rewind_video/) | Bestimmt, ob ein Video automatisch zum Anfang zurückgespult wird,<br/>            sobald der Film zu Ende abgespielt wurde.<br/>            Lesen/Schreiben **bool**. |
| [`play_loop_mode`](/slides/python-net/de/aspose.slides/videoframe/play_loop_mode/) | Bestimmt, ob ein Video wiederholt wird.<br/>            Lesen/Schreiben **bool**. |
| [`hide_at_showing`](/slides/python-net/de/aspose.slides/videoframe/hide_at_showing/) | Bestimmt, ob ein VideoFrame ausgeblendet ist.<br/>            Lesen/Schreiben **bool**. |
| [`volume`](/slides/python-net/de/aspose.slides/videoframe/volume/) | Gibt die Audio-Lautstärke zurück oder setzt sie.<br/>            Lesen/Schreiben [`AudioVolumeMode`](/slides/python-net/de/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/de/aspose.slides/videoframe/play_mode/) | Gibt den Videowiedergabemodus zurück oder setzt ihn.<br/>            Lesen/Schreiben [`VideoPlayModePreset`](/slides/python-net/de/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/de/aspose.slides/videoframe/full_screen_mode/) | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird.<br/>            Lesen/Schreiben **bool**. |
| [`link_path_long`](/slides/python-net/de/aspose.slides/videoframe/link_path_long/) | Gibt den Namen einer Videodatei zurück, die mit einem VideoFrame verknüpft ist, oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`embedded_video`](/slides/python-net/de/aspose.slides/videoframe/embedded_video/) | Gibt das eingebettete Videoobjekt zurück oder setzt es.<br/>            Lesen/Schreiben [`IVideo`](/slides/python-net/de/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/de/aspose.slides/videoframe/trim_from_start/) | Start zuschneiden [ms] |
| [`trim_from_end`](/slides/python-net/de/aspose.slides/videoframe/trim_from_end/) | Ende zuschneiden [ms] |
| [`caption_tracks`](/slides/python-net/de/aspose.slides/videoframe/caption_tracks/) | Gibt die Sammlung von Untertiteln zurück, die dem Video-Frame zugeordnet sind.<br/>             Diese Eigenschaft ist nur-lesbar und gibt ein [`ICaptionsCollection`](/slides/python-net/de/aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält. |

## Methoden

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/videoframe/get_image/#) | Gibt das Miniaturbild der Form zurück.<br/>            Der Standard-Typ ShapeThumbnailBounds.Shape wird für die Miniaturbild-Grenzen verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Gibt das Miniaturbild der Form zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/videoframe/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/videoframe/get_base_placeholder/#) | Gibt eine grundlegende Platzhalter-Form zurück (eine Form aus dem Layout und/oder der Master-Folie, von der die aktuelle Form erbt).<br/>            Gibt None zurück, wenn die aktuelle Form nicht geerbt ist. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/videoframe/get_visual_bounds/#) | Gibt die visuellen Grenzen der Form zurück, berechnet aus ihrem gerenderten Inhalt. |
| [`get_geometry_paths(self)`](/slides/python-net/de/aspose.slides/videoframe/get_geometry_paths/#) | Gibt eine Kopie des Pfads der geometrischen Form zurück. Die Koordinaten sind relativ zur linken oberen Ecke der Form. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/de/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Aktualisiert die Geometrie der Form aus dem [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)-Objekt. Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/de/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Aktualisiert die Geometrie der Form aus einem Array von [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath). Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/de/aspose.slides/videoframe/create_shape_elements/#) | Erstellt und gibt ein Array der Form-Elemente zurück. |

### Siehe auch
* Klasse [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape)
* Klasse [`PictureFrame`](/slides/python-net/de/aspose.slides/pictureframe)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Klasse [`VideoFrame`](/slides/python-net/de/aspose.slides/videoframe)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)