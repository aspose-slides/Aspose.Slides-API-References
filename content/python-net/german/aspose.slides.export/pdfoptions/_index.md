---
title: PdfOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/pdfoptions/
---
## PdfOptions Klasse

Stellt Optionen bereit, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.

**Vererbung:**[`PdfOptions`](/slides/python-net/de/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)

Der PdfOptions-Typ enthält die folgenden Mitglieder:

## Konstruktoren

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/pdfoptions/__init__/#) | Standardkonstruktor. |

## Eigenschaften

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/pdfoptions/warning_callback/) | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/pdfoptions/progress_callback/) | Stellt ein Callback-Objekt für Fortschrittsaktualisierungen beim Speichern in Prozent dar.<br/>            Siehe [`IProgressCallback`](/slides/python-net/de/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/pdfoptions/default_regular_font/) | Gibt die Schriftart zurück oder legt sie fest, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/pdfoptions/gradient_style/) | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`GradientStyle`](/slides/python-net/de/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/pdfoptions/skip_java_script_links/) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. <br/>            Lesen/Schreiben **bool**. Der Standardwert ist **false** . |
| [`slides_layout_options`](/slides/python-net/de/aspose.slides.export/pdfoptions/slides_layout_options/) | Ruft den Modus ab oder legt ihn fest, in dem Folien beim Exportieren einer Präsentation auf der Seite platziert werden [`ISlidesLayoutOptions`](/slides/python-net/de/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/de/aspose.slides.export/pdfoptions/ink_options/) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern.<br/>            Nur-Lesen [`IInkOptions`](/slides/python-net/de/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/de/aspose.slides.export/pdfoptions/show_hidden_slides/) | Gibt an, ob das erzeugte Dokument versteckte Folien einbeziehen soll oder nicht.<br/>            Standard ist `false`. |
| [`text_compression`](/slides/python-net/de/aspose.slides.export/pdfoptions/text_compression/) | Gibt den Kompressionstyp an, der für allen Textinhalt im Dokument verwendet wird.<br/>            Lesen/Schreiben [`PdfTextCompression`](/slides/python-net/de/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/de/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Zeigt an, ob für jedes Bild die effektivste Kompression (statt der Standardkompression) automatisch ausgewählt werden soll <br/>            automatisch. Wenn auf **bool**.true gesetzt, wird für jedes Bild in der Präsentation der am besten geeignete Kompressions-Algorithmus ausgewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt. <br/>            Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und erfordert <br/>            zusätzlichen RAM, und diese Option ist standardmäßig **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/de/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Bestimmt, ob Aspose.Slides gängige Schriftarten für ASCII-Text (Code-Bereich 33..127) einbetten soll.<br/>            Schriftarten für Zeichenkodierungen größer als 127 werden immer eingebettet.<br/>            Die Liste gängiger Schriftarten enthält die 14 Basis-Schriftarten von PDF und zusätzliche benutzerdefinierte Schriftarten.<br/>            Lesen/Schreiben **bool**. |
| [`additional_common_font_families`](/slides/python-net/de/aspose.slides.export/pdfoptions/additional_common_font_families/) | Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder legt es fest, die Aspose.Slides als gängig betrachten soll.<br/>            Lesen/Schreiben **str**[]. |
| [`embed_full_fonts`](/slides/python-net/de/aspose.slides.export/pdfoptions/embed_full_fonts/) | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein verwendetes Teilset.<br/>            Lesen/Schreiben **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/de/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Gibt an, ob Text rasterisiert als Bitmap gespeichert werden soll, wenn die Schriftart keine fette Formatierung unterstützt.<br/>            Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriftarten verbessern.<br/>            Lesen/Schreiben **bool**. |
| [`jpeg_quality`](/slides/python-net/de/aspose.slides.export/pdfoptions/jpeg_quality/) | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt.<br/>            Lesen/Schreiben **int**. |
| [`compliance`](/slides/python-net/de/aspose.slides.export/pdfoptions/compliance/) | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument.<br/>            Lesen/Schreiben [`PdfCompliance`](/slides/python-net/de/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/de/aspose.slides.export/pdfoptions/password/) | Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments.<br/>            Lesen/Schreiben **str**. |
| [`access_permissions`](/slides/python-net/de/aspose.slides.export/pdfoptions/access_permissions/) | Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte beim Öffnen des Dokuments mit Benutzerzugriff gewährt werden sollen<br/>            Siehe [`PdfAccessPermissions`](/slides/python-net/de/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/de/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren.<br/>            Lesen/Schreiben **bool**. |
| [`sufficient_resolution`](/slides/python-net/de/aspose.slides.export/pdfoptions/sufficient_resolution/) | Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt.<br/>            <br/>Die Eigenschaft beeinflusst Dateigröße, Exportdauer und Bildqualität.<br/><br/><br/>Der Standardwert ist **96** .<br/><br/><br/>            Lesen/Schreiben **float**. |
| [`draw_slides_frame`](/slides/python-net/de/aspose.slides.export/pdfoptions/draw_slides_frame/) | True, um um jede Folie einen schwarzen Rahmen zu zeichnen.<br/>             Lesen/Schreiben **bool**. |
| [`image_transparent_color`](/slides/python-net/de/aspose.slides.export/pdfoptions/image_transparent_color/) | Ruft die transparente Farbe des Bildes ab oder legt sie fest. |
| [`apply_image_transparent`](/slides/python-net/de/aspose.slides.export/pdfoptions/apply_image_transparent/) | Wendet die angegebene transparente Farbe auf ein Bild an, wenn `true`. |
| [`include_ole_data`](/slides/python-net/de/aspose.slides.export/pdfoptions/include_ole_data/) | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren.<br/>            Lesen/Schreiben **bool**. |


### Siehe auch
* Klasse [`PdfOptions`](/slides/python-net/de/aspose.slides.export/pdfoptions)
* Klasse [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)