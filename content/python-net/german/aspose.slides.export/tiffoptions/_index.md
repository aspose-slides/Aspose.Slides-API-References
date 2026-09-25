---
title: TiffOptions class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/tiffoptions/
---
## TiffOptions Klasse

Stellt Optionen bereit, die steuern, wie eine Präsentation im TIFF-Format gespeichert wird.

**Vererbung:**[`TiffOptions`](/slides/python-net/de/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)

Der TiffOptions-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/tiffoptions/__init__/#) | Standardkonstruktor. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/tiffoptions/warning_callback/) | Gibt ein Objekt zurück oder setzt es, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/tiffoptions/progress_callback/) | Stellt ein Rückrufobjekt für Fortschrittsaktualisierungen beim Speichern in Prozent dar.<br/>            Siehe [`IProgressCallback`](/slides/python-net/de/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/tiffoptions/default_regular_font/) | Gibt die Schriftart zurück oder setzt sie, die verwendet wird, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/tiffoptions/gradient_style/) | Gibt den visuellen Stil des Farbverlaufs zurück oder setzt ihn.<br/>            Lesen/Schreiben [`GradientStyle`](/slides/python-net/de/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/tiffoptions/skip_java_script_links/) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen.<br/>            Lesen/Schreiben **bool**. Der Standardwert ist **false** . |
| [`ink_options`](/slides/python-net/de/aspose.slides.export/tiffoptions/ink_options/) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern.<br/>            Nur lesen [`IInkOptions`](/slides/python-net/de/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/de/aspose.slides.export/tiffoptions/show_hidden_slides/) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht.<br/>            Standard ist `false`. |
| [`image_size`](/slides/python-net/de/aspose.slides.export/tiffoptions/image_size/) | Gibt die Größe eines erzeugten TIFF-Bildes an.<br/>            Standardwert ist 0x0, was bedeutet, dass die Bildgrößen basierend auf der Foliengröße der Präsentation berechnet werden.<br/>            Lesen/Schreiben [`Size`](/slides/python-net/de/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/de/aspose.slides.export/tiffoptions/dpi_x/) | Gibt die horizontale Auflösung in Punkten pro Zoll an.<br/>            Lesen/Schreiben **int**. |
| [`dpi_y`](/slides/python-net/de/aspose.slides.export/tiffoptions/dpi_y/) | Gibt die vertikale Auflösung in Punkten pro Zoll an.<br/>            Lesen/Schreiben **int**. |
| [`compression_type`](/slides/python-net/de/aspose.slides.export/tiffoptions/compression_type/) | Gibt den Kompressionstyp an.<br/>            Lesen/Schreiben [`TiffCompressionTypes`](/slides/python-net/de/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/de/aspose.slides.export/tiffoptions/pixel_format/) | Gibt das Pixelformat für die erzeugten Bilder an.<br/>            Lesen/Schreiben [`ImagePixelFormat`](/slides/python-net/de/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/de/aspose.slides.export/tiffoptions/slides_layout_options/) | Liest oder setzt den Modus, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird [`ISlidesLayoutOptions`](/slides/python-net/de/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/de/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Gibt den Algorithmus an, der ein Farbbild in ein Schwarz-Weiß-Bild umwandelt.<br/>            Diese Option wird nur angewendet, wenn [`TiffOptions.compression_type`](/slides/python-net/de/aspose.slides.export/tiffoptions/compression_type) <br/>            auf [`TiffCompressionTypes.CCITT4`](/slides/python-net/de/aspose.slides.export/tiffcompressiontypes/CCITT4) oder [`TiffCompressionTypes.CCITT3`](/slides/python-net/de/aspose.slides.export/tiffcompressiontypes/CCITT3) gesetzt ist<br/>            Lesen/Schreiben [`BlackWhiteConversionMode`](/slides/python-net/de/aspose.slides.export/blackwhiteconversionmode).<br/>            Standard ist [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/de/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Siehe auch
* Klasse [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)
* Klasse [`TiffOptions`](/slides/python-net/de/aspose.slides.export/tiffoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)