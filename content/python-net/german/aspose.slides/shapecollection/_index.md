---
title: ShapeCollection class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/
---
## ShapeCollection Klasse

Stellt eine Sammlung von Formen dar.

Der ShapeCollection-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`parent_group`](/slides/python-net/de/aspose.slides/shapecollection/parent_group/) | Gibt das übergeordnete Gruppenform-Objekt für die Formen-Sammlung zurück.<br/>            Nur-Lese [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |

Gibt das Element am angegebenen Index zurück.
            Nur-Lese [`IShape`](/slides/python-net/de/aspose.slides/ishape).

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides/shapecollection/__getitem__/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt<br/>            es am Ende der Formen-Sammlung hinzu. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/de/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt<br/>            es am Ende der Formen-Sammlung hinzu. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/de/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen,<br/>            und fügt es in die Formen-Sammlung an der angegebenen Position ein. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/de/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen,<br/>            und fügt es in die Formen-Sammlung an der angegebenen Position ein. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/de/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/de/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/de/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Erstellt einen neuen Zoom-Rahmen und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/de/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Erstellt einen neuen Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn in die Formen-Sammlung<br/>            an der angegebenen Position ein. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/de/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Erstellt einen neuen Abschnitts-Zoom-Rahmen und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/de/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Erstellt einen neuen Abschnitts-Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/de/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Erstellt einen neuen Abschnitts-Zoom-Rahmen und fügt ihn in die Formen-Sammlung an der angegebenen Position ein. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/de/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Erstellt einen neuen Abschnitts-Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn in die Formen-Sammlung<br/>            an der angegebenen Position ein. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/de/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Erstellt einen neuen OLE-Objekt-Rahmen und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/de/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Erstellt einen neuen OLE-Objekt-Rahmen und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/de/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Erstellt einen neuen OLE-Objekt-Rahmen und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/de/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Erstellt einen neuen OLE-Objekt-Rahmen und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/de/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Erstellt einen neuen Videorahmen und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/de/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Erstellt einen neuen Videorahmen und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/de/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Erstellt einen neuen Audio-Rahmen mit einer eingebetteten WAV-Datei und fügt ihn am Ende der<br/>            Formen-Sammlung hinzu. Die eingebettete Audiodatei wird zur Presentation.Audios-Sammlung hinzugefügt. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/de/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Erstellt einen neuen Audio-Rahmen und fügt ihn am Ende der Formen-Sammlung hinzu, wobei ein<br/>            vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/de/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Erstellt einen neuen Audio-Rahmen mit einer eingebetteten WAV-Datei und fügt ihn in die Formen-Sammlung<br/>            an der angegebenen Position ein. Die eingebettete Audiodatei wird zur Presentation.Audios<br/>            Sammlung hinzugefügt. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/de/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Erstellt einen neuen Audio-Rahmen und fügt ihn an der angegebenen Position in die Formen-Sammlung ein<br/>            unter Verwendung eines vorhandenen Audio-Objekts aus der Presentation.Audios-Liste. |
| [`to_array(self)`](/slides/python-net/de/aspose.slides/shapecollection/to_array/#) | Erstellt und gibt ein Array zurück, das alle Formen enthält. |
| [`to_array(self, start_index, count)`](/slides/python-net/de/aspose.slides/shapecollection/to_array/#int-int) | Erstellt und gibt ein Array zurück, das alle Formen im angegebenen Bereich enthält. |
| [`reorder(self, index, shape)`](/slides/python-net/de/aspose.slides/shapecollection/reorder/#int-ishape) | Verschiebt die angegebene Form an eine neue Position innerhalb der Formen-Sammlung. |
| [`reorder(self, index, shapes)`](/slides/python-net/de/aspose.slides/shapecollection/reorder/#int-listishape) | Verschiebt die angegebenen Formen innerhalb der Formen-Sammlung und platziert sie beginnend ab dem angegebenen Index. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Erstellt eine neue Autoform mit Standardformatierung und fügt sie am Ende der<br/>            Formen-Sammlung hinzu. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/de/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Erstellt eine neue Autoform und fügt sie am Ende der Formen-Sammlung hinzu, optional<br/>            mit Standard-Vorlagenformatierung initialisiert. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Erstellt eine neue Autoform und fügt sie an der angegebenen Position in die Formen-Sammlung ein,<br/>            wobei die Standard-Vorlagenformatierung angewendet wird. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/de/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Erstellt eine neue Autoform und fügt sie an der angegebenen Position in die Formen-Sammlung ein,<br/>            optional mit Standard-Vorlagenstil initialisiert. |
| [`add_group_shape(self)`](/slides/python-net/de/aspose.slides/shapecollection/add_group_shape/#) | Erstellt eine neue leere Gruppierungsform und fügt sie am Ende der Formen-Sammlung hinzu.<br/>            Der Rahmen der Gruppe passt sich automatisch an, um alle hinzugefügten Formen zu umfassen. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Erstellt eine neue Gruppierungsform, konvertiert das angegebene SVG-Bild in einzelne Formen,<br/>            und fügt die resultierende Gruppe am Ende der Formen-Sammlung hinzu. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Erstellt eine neue Verbindungslinie mit Standard-Vorlagenstil und fügt sie am Ende der<br/>            Formen-Sammlung hinzu. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/de/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Erstellt eine neue Verbindungslinie und fügt sie am Ende der Formen-Sammlung hinzu,<br/>            wobei optional der Standard-Vorlagenstil angewendet wird. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formen-Sammlung ein,<br/>            wobei der Standard-Vorlagenstil angewendet wird. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/de/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formen-Sammlung ein,<br/>            optional wird der Standard-Vorlagenstil angewendet. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/de/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu.<br/>            Die neue Form behält die Breite und Höhe von `source_shape` bei. |
| [`add_clone(self, source_shape)`](/slides/python-net/de/aspose.slides/shapecollection/add_clone/#ishape) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu.<br/>            Die geklonte Form behält die Position und Größe des Originals bei. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/de/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein.<br/>            Die neue Form behält die Breite und Höhe von `source_shape` bei. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/de/aspose.slides/shapecollection/insert_clone/#int-ishape) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein.<br/>            Die geklonte Form behält die Position und Größe des Originals bei. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/de/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Erstellt ein SmartArt-Diagramm und fügt es am Ende der Formen-Sammlung hinzu. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Erstellt einen neuen Zusammenfassungs-Zoom-Rahmen und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Erstellt einen neuen Zusammenfassungs-Zoom-Rahmen und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/de/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Erstellt einen neuen Videorahmen und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Erstellt einen neuen Audio-Rahmen, der mit einer CD-Spur verknüpft ist, und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Erstellt einen neuen Audio-Rahmen, der mit einer CD-Spur verknüpft ist, und fügt ihn in die Formen-Sammlung<br/>            an der angegebenen Position ein. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/de/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Erstellt einen neuen Audio-Rahmen, der mit einer externen Audiodatei verknüpft ist, und fügt ihn am Ende der<br/>            Formen-Sammlung hinzu. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/de/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Erstellt einen neuen Audio-Rahmen, der mit einer externen Audiodatei verknüpft ist, und fügt ihn in die Formen-Sammlung<br/>            an der angegebenen Position ein. |
| [`index_of(self, shape)`](/slides/python-net/de/aspose.slides/shapecollection/index_of/#ishape) | Gibt den nullbasierten Index des ersten Auftretens der angegebenen Form in der Sammlung zurück. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/de/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Erstellt eine neue Rechteck-Autoform zur Darstellung mathematischer Inhalte und fügt sie am Ende der<br/>            Formen-Sammlung hinzu. |
| [`insert_group_shape(self, index)`](/slides/python-net/de/aspose.slides/shapecollection/insert_group_shape/#int) | Erstellt eine neue leere Gruppierungsform und fügt sie an der angegebenen Position in die Formen-Sammlung ein.<br/>            Der Rahmen der Gruppe passt sich automatisch an, um alle hinzugefügten Formen zu umfassen. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/de/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn am Ende der<br/>            Formen-Sammlung hinzu. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/de/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn in die Formen-Sammlung<br/>            an der angegebenen Position ein. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/de/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Erstellt eine neue Tabelle und fügt sie am Ende der Formen-Sammlung hinzu. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/de/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Erstellt eine neue Tabelle und fügt sie an der angegebenen Position in die Formen-Sammlung ein. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides/shapecollection/remove_at/#int) | Entfernt die Form am angegebenen Index aus der Formen-Sammlung. |
| [`remove(self, shape)`](/slides/python-net/de/aspose.slides/shapecollection/remove/#ishape) | Entfernt das erste Auftreten der angegebenen Form aus der Formen-Sammlung. |
| [`clear(self)`](/slides/python-net/de/aspose.slides/shapecollection/clear/#) | Entfernt alle Formen aus der Formen-Sammlung. |

### Siehe Auch
* Klasse [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)