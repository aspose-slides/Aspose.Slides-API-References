---
title: SVGOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/svgoptions/
---
## SVGOptions Klasse

Stellt SVG-Optionen dar.

**Vererbung:**[`SVGOptions`](/slides/python-net/de/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)

Der SVGOptions-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/svgoptions/__init__/#) | Initialisiert eine neue Instanz der SVGOptions-Klasse. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/de/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Initialisiert eine neue Instanz der SVGOptions-Klasse und gibt das Link-Einbettungssteuerelement-Objekt an. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/svgoptions/warning_callback/) | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/svgoptions/progress_callback/) | Stellt ein Callback-Objekt für das Speichern von Fortschrittsupdates in Prozent dar.<br/>            Siehe [`IProgressCallback`](/slides/python-net/de/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/svgoptions/default_regular_font/) | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/svgoptions/gradient_style/) | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`GradientStyle`](/slides/python-net/de/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/svgoptions/skip_java_script_links/) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen.<br/>            Lesen/Schreiben **bool**. Der Standardwert ist **false**. |
| [`ink_options`](/slides/python-net/de/aspose.slides.export/svgoptions/ink_options/) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern.<br/>            Nur lesen [`IInkOptions`](/slides/python-net/de/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/de/aspose.slides.export/svgoptions/use_frame_size/) | Bestimmt, ob der Textrahmen in einen Renderbereich einbezogen wird oder nicht.<br/>            Lesen/Schreiben **bool**.<br/>            Der Standardwert ist **false**. |
| [`use_frame_rotation`](/slides/python-net/de/aspose.slides.export/svgoptions/use_frame_rotation/) | Bestimmt, ob die angegebene Drehung der Form beim Rendern ausgeführt wird oder nicht.<br/>            Lesen/Schreiben **bool**.<br/>            Der Standardwert ist **true**. |
| [`vectorize_text`](/slides/python-net/de/aspose.slides.export/svgoptions/vectorize_text/) | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird.<br/>            Lesen/Schreiben **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/de/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder legt sie fest.<br/>            Lesen/Schreiben **int**. |
| [`disable_3d_text`](/slides/python-net/de/aspose.slides.export/svgoptions/disable_3d_text/) | Bestimmt, ob der 3D-Text in SVG deaktiviert ist.<br/>            Lesen/Schreiben **bool**. |
| [`disable_gradient_split`](/slides/python-net/de/aspose.slides.export/svgoptions/disable_gradient_split/) | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Farbverläufen.<br/>            Lesen/Schreiben **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/de/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 kann keine Einrückungen für Marker definieren.<br/>            Die Aspose.Slides SVG-Schreibengine hat einen Workaround für dieses Problem:<br/>            Sie schneidet das Ende der Linie mit Pfeil ab, sodass die Linie die Marker nicht überlappt.<br/>            Diese Option deaktiviert dieses Verhalten.<br/>            Lesen/Schreiben **bool**. |
| [`default`](/slides/python-net/de/aspose.slides.export/svgoptions/default/) | Gibt die Standardeinstellungen zurück.<br/>            Nur lesen [`SVGOptions`](/slides/python-net/de/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/de/aspose.slides.export/svgoptions/simple/) | Gibt die Einstellungen für die einfachste und kleinste SVG-Dateigenerierung zurück.<br/>            Nur lesen [`SVGOptions`](/slides/python-net/de/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/de/aspose.slides.export/svgoptions/wysiwyg/) | Gibt die Einstellungen für die genaueste SVG-Dateigenerierung zurück.<br/>            Nur lesen [`SVGOptions`](/slides/python-net/de/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/de/aspose.slides.export/svgoptions/jpeg_quality/) | Bestimmt die JPEG-Codierungsqualität.<br/>            Lesen/Schreiben **int**. |
| [`shape_formatting_controller`](/slides/python-net/de/aspose.slides.export/svgoptions/shape_formatting_controller/) | Gibt eine Callback-Schnittstelle zurück und legt sie fest, die dem Benutzer die Kontrolle über die Formkonvertierung ermöglicht.<br/>            Lesen/Schreiben [`ISvgShapeFormattingController`](/slides/python-net/de/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/de/aspose.slides.export/svgoptions/pictures_compression/) | Stellt das Kompressionsniveau der Bilder dar |
| [`delete_pictures_cropped_areas`](/slides/python-net/de/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn **true**, werden die beschnittenen <br/>            Teile entfernt, wenn **false**, werden sie im Dokument serialisiert (was zu einer <br/>            größeren Datei führen kann) |
| [`external_fonts_handling`](/slides/python-net/de/aspose.slides.export/svgoptions/external_fonts_handling/) | Bestimmt die Vorgehensweise beim Umgang mit extern geladenen Schriftarten.<br/>            Lesen/Schreiben [`SvgExternalFontsHandling`](/slides/python-net/de/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/de/aspose.slides.export/svgoptions/disable_font_ligatures/) | Gibt an, ob Text ohne Ligaturen gerendert wird, oder legt diesen Wert fest.<br/>            Wenn auf `true` gesetzt, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt. |

### Siehe auch
* Klasse [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)
* Klasse [`SVGOptions`](/slides/python-net/de/aspose.slides.export/svgoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)