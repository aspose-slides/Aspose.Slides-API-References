---
title: IPdfOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/ipdfoptions/
---
## IPdfOptions Klasse

Stellt Optionen bereit, die steuern, wie eine Präsentation im PDF-Format gespeichert wird.

Der IPdfOptions-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`text_compression`](/slides/python-net/de/aspose.slides.export/ipdfoptions/text_compression/) | Gibt den Kompressionstyp an, der für alle Textinhalte im Dokument verwendet wird.<br/>            Read/write [`PdfTextCompression`](/slides/python-net/de/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/de/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Zeigt an, ob die effektivste Kompression (statt der standardmäßigen) für jedes Bild ausgewählt werden muss <br/>            automatisch. Wenn auf **bool**.true gesetzt, wird für jedes Bild in der Präsentation die am besten geeignete Kompressions-<br/>            algorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt. <br/>            Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und verbraucht <br/>            zusätzlichen Arbeitsspeicher, und diese Option ist standardmäßig **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/de/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | True, um TrueType-Schriften für ASCII-Zeichen 32-127 einzubetten.<br/>            Schriften für Zeichen-Codes größer als 127 werden immer eingebettet.<br/>            Read/write **bool**. |
| [`show_hidden_slides`](/slides/python-net/de/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht.<br/>            Standardwert ist `false`. |
| [`additional_common_font_families`](/slides/python-net/de/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder legt es fest, die Aspose.Slides als üblich betrachten soll.<br/>            Read/write **str**[]. |
| [`embed_full_fonts`](/slides/python-net/de/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Bestimmt, ob alle Zeichen der Schrift eingebettet werden sollen oder nur ein Teil davon.<br/>            Read/write **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/de/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Zeigt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schrift keine Fettdarstellung unterstützt.<br/>            Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriften verbessern.<br/>            Read/write **bool**. |
| [`jpeg_quality`](/slides/python-net/de/aspose.slides.export/ipdfoptions/jpeg_quality/) | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt.<br/>            Read/write **int**. |
| [`compliance`](/slides/python-net/de/aspose.slides.export/ipdfoptions/compliance/) | Gewünschtes Konformitätslevel für das erzeugte PDF-Dokument.<br/>            Read/write [`PdfCompliance`](/slides/python-net/de/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/de/aspose.slides.export/ipdfoptions/password/) | Festlegen des Benutzerkennworts zum Schutz des PDF-Dokuments. <br/>            Read/write **str**. |
| [`access_permissions`](/slides/python-net/de/aspose.slides.export/ipdfoptions/access_permissions/) | Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird<br/>            Siehe [`PdfAccessPermissions`](/slides/python-net/de/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/de/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren.<br/>            Read/write **bool**. |
| [`sufficient_resolution`](/slides/python-net/de/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt.<br/>            <br/>Die Eigenschaft wirkt sich auf Dateigröße, Exportzeit und Bildqualität aus.<br/><br/><br/>Der Standardwert ist **96** .<br/><br/><br/>            Read/write **float**. |
| [`draw_slides_frame`](/slides/python-net/de/aspose.slides.export/ipdfoptions/draw_slides_frame/) | True, um einen schwarzen Rahmen um jede Folie zu zeichnen.<br/>             Read/write **bool**. |
| [`slides_layout_options`](/slides/python-net/de/aspose.slides.export/ipdfoptions/slides_layout_options/) | Liest oder setzt den Modus, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird [`ISlidesLayoutOptions`](/slides/python-net/de/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/de/aspose.slides.export/ipdfoptions/image_transparent_color/) | Liest oder setzt die transparente Farbe des Bildes. |
| [`apply_image_transparent`](/slides/python-net/de/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Wendet die angegebene transparente Farbe auf ein Bild an, wenn `true`. |
| [`ink_options`](/slides/python-net/de/aspose.slides.export/ipdfoptions/ink_options/) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern.<br/>            Read-only [`IInkOptions`](/slides/python-net/de/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/de/aspose.slides.export/ipdfoptions/include_ole_data/) | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren.<br/>            Read/write **bool**. |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### Siehe auch
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)