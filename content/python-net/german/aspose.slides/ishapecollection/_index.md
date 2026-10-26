---
title: IShapeCollection class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/
---
## IShapeCollection Klasse

Stellt eine Sammlung von Formen dar.

Der Typ IShapeCollection stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`parent_group`](/slides/python-net/de/aspose.slides/ishapecollection/parent_group/) | Liefert das übergeordnete Gruppierungsform-Objekt für die Formensammlung.<br/>            Nur-Lesen [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |

Liefert das Element am angegebenen Index. Nur-Lesen [`IShape`](/slides/python-net/de/aspose.slides/ishape).

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides/ishapecollection/__getitem__/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten für die Reihen und Einstellungen und fügt<br/>            es am Ende der Formensammlung hinzu. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/de/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten für die Reihen und Einstellungen und fügt<br/>            es am Ende der Formensammlung hinzu. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten für die Reihen und Einstellungen,<br/>            und fügt es in die Formensammlung an dem angegebenen Index ein. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten für die Reihen und Einstellungen,<br/>            und fügt es in die Formensammlung an dem angegebenen Index ein. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/de/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/de/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Erstellt einen neuen OLE-Objektrahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Erstellt einen neuen OLE-Objektrahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/de/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/de/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Erstellt einen neuen Zoom-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Erstellt einen neuen Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn in die Formensammlung<br/>            an dem angegebenen Index ein. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/de/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Erstellt einen neuen Abschnitts-Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/de/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Erstellt einen neuen Abschnitts-Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn am Ende der<br/>            Formensammlung hinzu. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Erstellt einen neuen Abschnitts-Zoom-Rahmen und fügt ihn in die Formensammlung an dem<br/>            angegebenen Index ein. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Erstellt einen neuen Abschnitts-Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn in die Formensammlung<br/>            an dem angegebenen Index ein. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/de/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Erstellt einen neuen Video-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/de/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Erstellt einen neuen Video-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/de/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Erstellt einen neuen Audio-Rahmen mit einer eingebetteten WAV-Datei und fügt ihn am Ende der<br/>            Formensammlung hinzu. Der eingebettete Ton wird zur Presentation.Audios-Sammlung hinzugefügt. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/de/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Erstellt einen neuen Audio-Rahmen und fügt ihn am Ende der Formensammlung hinzu, wobei ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Erstellt einen neuen Audio-Rahmen mit einer eingebetteten WAV-Datei und fügt ihn an dem angegebenen Index in die Formensammlung ein. Der eingebettete Ton wird zur Presentation.Audios<br/>            Sammlung hinzugefügt. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Erstellt einen neuen Audio-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein,<br/>            wobei ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird. |
| [`to_array(self)`](/slides/python-net/de/aspose.slides/ishapecollection/to_array/#) | Erstellt und gibt ein Array zurück, das alle Formen enthält. |
| [`to_array(self, start_index, count)`](/slides/python-net/de/aspose.slides/ishapecollection/to_array/#int-int) | Erstellt und gibt ein Array zurück, das alle Formen im angegebenen Bereich enthält. |
| [`reorder(self, index, shape)`](/slides/python-net/de/aspose.slides/ishapecollection/reorder/#int-ishape) | Verschiebt die angegebene Form an eine neue Position innerhalb der Formensammlung. |
| [`reorder(self, index, shapes)`](/slides/python-net/de/aspose.slides/ishapecollection/reorder/#int-listishape) | Verschiebt die angegebenen Formen innerhalb der Formensammlung und legt sie ab dem angegebenen Index ab. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Erstellt eine neue AutoForm mit Standardformatierung und fügt sie am Ende der<br/>            Formensammlung hinzu. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/de/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Erstellt eine neue AutoForm und fügt sie am Ende der Formensammlung hinzu, optional<br/>            mit standardmäßiger Vorlagenformatierung initialisiert. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Erstellt eine neue AutoForm und fügt sie an dem angegebenen Index in die Formensammlung ein,<br/>            wobei die Standardvorlagenformatierung angewendet wird. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Erstellt eine neue AutoForm und fügt sie an dem angegebenen Index in die Formensammlung ein,<br/>            optional mit standardmäßiger Vorlagenformatierung initialisiert. |
| [`add_group_shape(self)`](/slides/python-net/de/aspose.slides/ishapecollection/add_group_shape/#) | Erstellt eine neue leere Gruppierungsform und fügt sie am Ende der Formensammlung hinzu.<br/>            Der Rahmen der Gruppe passt sich automatisch an, um alle hinzugefügten Formen aufzunehmen. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Erstellt eine neue Gruppierungsform, konvertiert das angegebene SVG-Bild in einzelne Formen,<br/>            und fügt die resultierende Gruppe am Ende der Formensammlung hinzu. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Erstellt eine neue Verbinder-Form mit Standardvorlagenstil und fügt sie am Ende der<br/>            Formensammlung hinzu. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/de/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Erstellt eine neue Verbinder-Form und fügt sie am Ende der Formensammlung hinzu,<br/>            optional mit Standardvorlagenstil. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Erstellt eine neue Verbinder-Form und fügt sie an dem angegebenen Index in die Formensammlung ein,<br/>            wobei der Standardvorlagenstil angewendet wird. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Erstellt eine neue Verbinder-Form und fügt sie an dem angegebenen Index in die Formensammlung ein,<br/>            optional mit Standardvorlagenstil. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/de/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu.<br/>            Die neue Form behält die Breite und Höhe von `source_shape` bei. |
| [`add_clone(self, source_shape)`](/slides/python-net/de/aspose.slides/ishapecollection/add_clone/#ishape) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu.<br/>            Die geklonte Form behält Position und Größe des Originals bei. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Erstellt eine Kopie der angegebenen Form und fügt sie an dem angegebenen Index in die Formensammlung ein. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Erstellt eine Kopie der angegebenen Form und fügt sie an dem angegebenen Index in die Formensammlung ein.<br/>            Die neue Form behält die Breite und Höhe von `source_shape` bei. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Erstellt eine Kopie der angegebenen Form und fügt sie an dem angegebenen Index in die Formensammlung ein.<br/>            Die geklonte Form behält Position und Größe des Originals bei. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/de/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Erstellt ein SmartArt-Diagramm und fügt es am Ende der Formensammlung hinzu. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Erstellt einen neuen Summary-Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Erstellt einen neuen Summary-Zoom-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Erstellt einen neuen Video-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Erstellt einen neuen Audio-Rahmen, der mit einem CD-Track verknüpft ist, und fügt ihn am Ende der Formensammlung hinzu. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Erstellt einen neuen Audio-Rahmen, der mit einem CD-Track verknüpft ist, und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/de/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Erstellt einen neuen Audio-Rahmen, der mit einer externen Audiodatei verknüpft ist, und fügt ihn am Ende der<br/>            Formensammlung hinzu. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Erstellt einen neuen Audio-Rahmen, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an dem angegebenen Index in die<br/>            Formensammlung ein. |
| [`index_of(self, shape)`](/slides/python-net/de/aspose.slides/ishapecollection/index_of/#ishape) | Gibt den nullbasierten Index des ersten Auftretens der angegebenen Form in der Sammlung zurück. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/de/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Erstellt eine neue Rechteck-AutoForm zur Darstellung mathematischer Inhalte und fügt sie am Ende der<br/>            Formensammlung hinzu. |
| [`insert_group_shape(self, index)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_group_shape/#int) | Erstellt eine neue leere Gruppierungsform und fügt sie an dem angegebenen Index in die Formensammlung ein.<br/>            Der Rahmen der Gruppe passt sich automatisch an, um alle hinzugefügten Formen aufzunehmen. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/de/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Erstellt einen neuen Bild-Rahmen mit dem angegebenen Bild und fügt ihn am Ende der<br/>            Formensammlung hinzu. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Erstellt einen neuen Bild-Rahmen mit dem angegebenen Bild und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/de/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Erstellt eine neue Tabelle und fügt sie am Ende der Formensammlung hinzu. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/de/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Erstellt eine neue Tabelle und fügt sie an dem angegebenen Index in die Formensammlung ein. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides/ishapecollection/remove_at/#int) | Entfernt die Form am angegebenen Index aus der Formensammlung. |
| [`remove(self, shape)`](/slides/python-net/de/aspose.slides/ishapecollection/remove/#ishape) | Entfernt das erste Auftreten der angegebenen Form aus der Formensammlung. |
| [`clear(self)`](/slides/python-net/de/aspose.slides/ishapecollection/clear/#) | Entfernt alle Formen aus der Formensammlung. |

### Siehe Auch
* Klasse [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)