---
title: AudioFrame class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/audioframe/
---
## AudioFrame Klasse

Represents an audio clip on a slide.

**Inheritance:**[`AudioFrame`](/slides/python-net/de/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/de/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

The AudioFrame type exposes the following members:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/audioframe/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            **Nur lesend** **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides/audioframe/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur lesend [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides/audioframe/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur lesend [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides/audioframe/raw_frame/) | Gibt die rohen Eigenschaften des Formrahmens zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides/audioframe/frame/) | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides/audioframe/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formen, die keine Linieneigenschaften besitzen, None zurückgeben.<br/>            Nur lesend [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides/audioframe/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formen, die keine 3D-Eigenschaften besitzen, None zurückgeben.<br/>            Nur lesend [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides/audioframe/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte auf eine Form anwendet.<br/>            Hinweis: Kann für bestimmte Formen, die keine Effekt-Eigenschaften besitzen, None zurückgeben.<br/>            Nur lesend [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides/audioframe/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält.<br/>            Hinweis: Kann für bestimmte Formen, die keine Füll-Eigenschaften besitzen, None zurückgeben.<br/>            Nur lesend [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/audioframe/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/audioframe/hyperlink_mouse_over/) | Gibt den für Mausüberlauf definierten Hyperlink zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/audioframe/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur lesend [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides/audioframe/hidden/) | Bestimmt, ob die Form versteckt ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides/audioframe/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form ganz hinten in der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form ganz vorne in der Z-Reihenfolge zurück.<br/>            Nur lesend **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/audioframe/connection_site_count/) | Gibt die Anzahl der Anschlusspunkte an der Form zurück.<br/>            Nur lesend **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides/audioframe/rotation/) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder legt sie fest.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert<br/>            bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides/audioframe/x/) | Liest oder setzt die X-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides/audioframe/y/) | Liest oder setzt die Y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides/audioframe/width/) | Liest oder setzt die Breite der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides/audioframe/height/) | Liest oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/audioframe/black_white_mode/) | Eigenschaft gibt an, wie eine Form im Schwarz-Weiße-Anzeigemodus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides/audioframe/unique_id/) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der von Add-Ins oder anderem Code verwendet werden kann.<br/>            Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als dauerhafter eindeutiger Schlüssel behandelt werden.<br/>            Nur lesend **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/audioframe/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der während der gesamten Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, zuverlässig von überall im Dokument auf die Form zu verweisen.<br/>            Nur lesend **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides/audioframe/alternative_text/) | Gibt den alternativen Text zurück, der einer Form zugeordnet ist, oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/audioframe/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück, der einer Form zugeordnet ist, oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides/audioframe/name/) | Gibt den Namen einer Form zurück oder legt ihn fest.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren String.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides/audioframe/is_decorative/) | Liest oder setzt die Option 'Mark as decorative'<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides/audioframe/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesend [`IPictureFrameLock`](/slides/python-net/de/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides/audioframe/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur lesend **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides/audioframe/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls gibt sie None zurück.<br/>            Nur lesend [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides/audioframe/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Nur lesend [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/audioframe/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur lesend [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/de/aspose.slides/audioframe/shape_style/) | Gibt das Style-Objekt der Form zurück.<br/>            Nur lesend [`IShapeStyle`](/slides/python-net/de/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/de/aspose.slides/audioframe/shape_type/) | Liest oder setzt den AutoShape-Typ für einen PictureFrame.<br/>            Alle Elemente des Satzes [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) sind zulässig,<br/>            außer allen Arten von Linien:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lesen/Schreiben [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/de/aspose.slides/audioframe/adjustments/) | Gibt eine Sammlung der Anpassungswerte einer Form zurück.<br/>            Nur lesend [`IAdjustValueCollection`](/slides/python-net/de/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/de/aspose.slides/audioframe/picture_frame_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur lesend [`IPictureFrameLock`](/slides/python-net/de/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/de/aspose.slides/audioframe/picture_format/) | Gibt das PictureFillFormat-Objekt für einen Bildrahmen zurück.<br/>            Nur lesend [`IPictureFillFormat`](/slides/python-net/de/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/de/aspose.slides/audioframe/relative_scale_height/) | Gibt die Höheskala (relativ zur Originalbildgröße) des Bildrahmens zurück oder legt sie fest. Wert 1,0 entspricht 100 %.<br/>            Lesen/Schreiben **float**. |
| [`relative_scale_width`](/slides/python-net/de/aspose.slides/audioframe/relative_scale_width/) | Gibt die Breiteskala (relativ zur Originalbildgröße) des Bildrahmens zurück oder legt sie fest. Wert 1,0 entspricht 100 %.<br/>            Lesen/Schreiben **float**. |
| [`is_cameo`](/slides/python-net/de/aspose.slides/audioframe/is_cameo/) | Bestimmt, ob der PictureFrame ein Cameo-Objekt ist oder nicht.<br/>            Nur lesend **bool**. |
| [`audio_cd_start_track`](/slides/python-net/de/aspose.slides/audioframe/audio_cd_start_track/) | Gibt den Start-Track-Index zurück oder legt ihn fest.<br/>            Lesen/Schreiben **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/de/aspose.slides/audioframe/audio_cd_start_track_time/) | Gibt die Start-Track-Zeit zurück oder legt sie fest.<br/>            Lesen/Schreiben **int**. |
| [`audio_cd_end_track`](/slides/python-net/de/aspose.slides/audioframe/audio_cd_end_track/) | Gibt den letzten Track-Index zurück oder legt ihn fest.<br/>            Lesen/Schreiben **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/de/aspose.slides/audioframe/audio_cd_end_track_time/) | Gibt die letzte Track-Zeit zurück oder legt sie fest.<br/>            Lesen/Schreiben **int**. |
| [`volume`](/slides/python-net/de/aspose.slides/audioframe/volume/) | Gibt die Audio-Lautstärke zurück oder legt sie fest.<br/>            Lesen/Schreiben [`AudioVolumeMode`](/slides/python-net/de/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/de/aspose.slides/audioframe/play_mode/) | Gibt den Audio-Wiedergabemodus zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`AudioPlayModePreset`](/slides/python-net/de/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/de/aspose.slides/audioframe/hide_at_showing/) | Bestimmt, ob ein AudioFrame verborgen ist.<br/>            Lesen/Schreiben **bool**. |
| [`play_loop_mode`](/slides/python-net/de/aspose.slides/audioframe/play_loop_mode/) | Bestimmt, ob ein Audio in Schleife wiedergegeben wird.<br/>            Lesen/Schreiben **bool**. |
| [`play_across_slides`](/slides/python-net/de/aspose.slides/audioframe/play_across_slides/) | Bestimmt, ob Audio über die Folien hinweg abgespielt wird.<br/>            Lesen/Schreiben **bool**. |
| [`rewind_audio`](/slides/python-net/de/aspose.slides/audioframe/rewind_audio/) | Bestimmt, ob Audio nach dem Abspielen automatisch zum Beginn zurückgespult wird.<br/>            Lesen/Schreiben **bool**. |
| [`embedded`](/slides/python-net/de/aspose.slides/audioframe/embedded/) | Bestimmt, ob ein Sound in die Präsentation eingebettet ist.<br/>            Nur lesend **bool**. |
| [`link_path_long`](/slides/python-net/de/aspose.slides/audioframe/link_path_long/) | Gibt den Namen einer Audiodatei zurück, die mit einem AudioFrame verknüpft ist, oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`embedded_audio`](/slides/python-net/de/aspose.slides/audioframe/embedded_audio/) | Gibt das eingebettete Audio-Objekt zurück oder legt es fest.<br/>            Lesen/Schreiben [`IAudio`](/slides/python-net/de/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/de/aspose.slides/audioframe/fade_in_duration/) | Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an.<br/>            Lesen/Schreiben **float**. |
| [`fade_out_duration`](/slides/python-net/de/aspose.slides/audioframe/fade_out_duration/) | Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an.<br/>            Lesen/Schreiben **float**. |
| [`volume_value`](/slides/python-net/de/aspose.slides/audioframe/volume_value/) | Gibt die Audio-Lautstärke in Prozent zurück oder legt sie fest.<br/>            Lesen/Schreiben **float**. |
| [`trim_from_start`](/slides/python-net/de/aspose.slides/audioframe/trim_from_start/) | Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt wird, in Millisekunden.<br/>            Lesen/Schreiben **float**. |
| [`trim_from_end`](/slides/python-net/de/aspose.slides/audioframe/trim_from_end/) | Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt wird, in Millisekunden.<br/>            Lesen/Schreiben **float**. |
| [`caption_tracks`](/slides/python-net/de/aspose.slides/audioframe/caption_tracks/) | Liest die Sammlung der geschlossenen Untertitel, die dem AudioFrame zugeordnet sind.<br/>            Diese Eigenschaft ist nur lesend und gibt ein [`ICaptionsCollection`](/slides/python-net/de/aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/audioframe/get_image/#) | Gibt das Form-Miniaturbild zurück.<br/>            Der Standard-Typ ShapeThumbnailBounds.Shape für die Miniaturbild-Grenzen wird verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Gibt das Form-Miniaturbild zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/audioframe/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/audioframe/get_base_placeholder/#) | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form ererbt wird).<br/>            Gibt None zurück, wenn die aktuelle Form nicht vererbt ist. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides/audioframe/get_visual_bounds/#) | Liest die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [`get_geometry_paths(self)`](/slides/python-net/de/aspose.slides/audioframe/get_geometry_paths/#) | Gibt eine Kopie des Pfads der geometrischen Form zurück. Koordinaten sind relativ zur linken oberen Ecke der Form. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/de/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Aktualisiert die Geometrie der Form aus dem [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)-Objekt. Koordinaten müssen relativ zur linken<br/>             oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/de/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Aktualisiert die Geometrie der Form aus einem Array von [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath). Koordinaten müssen relativ zur linken<br/>             oberen Ecke der Form sein.<br/>             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/de/aspose.slides/audioframe/create_shape_elements/#) | Erstellt und gibt ein Array der Form-Elemente zurück. |

### Siehe auch
* Klasse [`AudioFrame`](/slides/python-net/de/aspose.slides/audioframe)
* Klasse [`GeometryShape`](/slides/python-net/de/aspose.slides/geometryshape)
* Klasse [`PictureFrame`](/slides/python-net/de/aspose.slides/pictureframe)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)