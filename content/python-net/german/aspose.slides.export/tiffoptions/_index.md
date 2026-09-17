---
title: TiffOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/tiffoptions/
---
## TiffOptions Klasse

Provides options that control how a presentation is saved in TIFF format.

**Vererbung:**[`TiffOptions`](/slides/python-net/de/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)

Der TiffOptions Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/tiffoptions/__init__/#) | Standardkonstruktor. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/tiffoptions/warning_callback/) | Gibt ein Objekt zurück bzw. setzt ein Objekt, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/tiffoptions/progress_callback/) | Stellt ein Callback-Objekt für die Aktualisierung des Speichervorgangs in Prozent dar.<br/>            Siehe [`IProgressCallback`](/slides/python-net/de/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/tiffoptions/default_regular_font/) | Gibt die Schriftart zurück oder setzt sie, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/tiffoptions/gradient_style/) | Gibt den visuellen Stil des Farbverlaufs zurück oder setzt ihn.<br/>            Lesen/Schreiben [`GradientStyle`](/slides/python-net/de/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/tiffoptions/skip_java_script_links/) | Legt fest, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. <br/>            Lesen/Schreiben **bool**. Der Standardwert ist **false** . |
| [`ink_options`](/slides/python-net/de/aspose.slides.export/tiffoptions/ink_options/) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern.<br/>            Nur-Lesen [`IInkOptions`](/slides/python-net/de/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/de/aspose.slides.export/tiffoptions/show_hidden_slides/) | Legt fest, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht.<br/>            Standard ist `false`. |
| [`image_size`](/slides/python-net/de/aspose.slides.export/tiffoptions/image_size/) | Legt die Größe eines erzeugten TIFF-Bildes fest.<br/>            Der Standardwert ist 0x0, was bedeutet, dass die Größe des erzeugten Bildes anhand der Foliengröße der Präsentation berechnet wird.<br/>            Lesen/Schreiben **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/de/aspose.slides.export/tiffoptions/dpi_x/) | Legt die horizontale Auflösung in Punkten pro Zoll fest.<br/>            Lesen/Schreiben **int**. |
| [`dpi_y`](/slides/python-net/de/aspose.slides.export/tiffoptions/dpi_y/) | Legt die vertikale Auflösung in Punkten pro Zoll fest.<br/>            Lesen/Schreiben **int**. |
| [`compression_type`](/slides/python-net/de/aspose.slides.export/tiffoptions/compression_type/) | Legt den Kompressionstyp fest.<br/>            Lesen/Schreiben [`TiffCompressionTypes`](/slides/python-net/de/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/de/aspose.slides.export/tiffoptions/pixel_format/) | Legt das Pixelformat für die erzeugten Bilder fest.<br/>            Lesen/Schreiben [`ImagePixelFormat`](/slides/python-net/de/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/de/aspose.slides.export/tiffoptions/slides_layout_options/) | Liest oder setzt den Modus, in dem Folien beim Export einer Präsentation auf der Seite platziert werden [`ISlidesLayoutOptions`](/slides/python-net/de/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/de/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Legt den Algorithmus zum Konvertieren eines Farbbildes in ein Schwarzweißbild fest.<br/>            Diese Option wird nur angewendet, wenn [`TiffOptions.compression_type`](/slides/python-net/de/aspose.slides.export/tiffoptions/compression_type) <br/>            auf [`TiffCompressionTypes.CCITT4`](/slides/python-net/de/aspose.slides.export/tiffcompressiontypes/CCITT4) oder [`TiffCompressionTypes.CCITT3`](/slides/python-net/de/aspose.slides.export/tiffcompressiontypes/CCITT3) gesetzt ist<br/>            Lesen/Schreiben [`BlackWhiteConversionMode`](/slides/python-net/de/aspose.slides.export/blackwhiteconversionmode).<br/>            Standard ist [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/de/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Siehe auch
* Klasse [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)
* Klasse [`TiffOptions`](/slides/python-net/de/aspose.slides.export/tiffoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)