---
title: ITiffOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/itiffoptions/
---
## ITiffOptions Klasse

Stellt Optionen bereit, die steuern, wie eine Präsentation im TIFF-Format gespeichert wird.

Der Typ ITiffOptions stellt die folgenden Member bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`image_size`](/slides/python-net/de/aspose.slides.export/itiffoptions/image_size/) | Gibt die Größe eines erzeugten TIFF-Bildes an.<br/>            Der Standardwert ist 0x0, was bedeutet, dass die Bildgrößen basierend auf dem Wert der Präsentationsfoliengröße berechnet werden.<br/>            Lesen/Schreiben [`Size`](/slides/python-net/de/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/de/aspose.slides.export/itiffoptions/dpi_x/) | Gibt die horizontale Auflösung in Punkten pro Zoll an.<br/>            Lesen/Schreiben **int**. |
| [`dpi_y`](/slides/python-net/de/aspose.slides.export/itiffoptions/dpi_y/) | Gibt die vertikale Auflösung in Punkten pro Zoll an.<br/>            Lesen/Schreiben **int**. |
| [`show_hidden_slides`](/slides/python-net/de/aspose.slides.export/itiffoptions/show_hidden_slides/) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht.<br/>            Standard ist `false`. |
| [`compression_type`](/slides/python-net/de/aspose.slides.export/itiffoptions/compression_type/) | Gibt den Kompressionstyp an.<br/>            Lesen/Schreiben [`TiffCompressionTypes`](/slides/python-net/de/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/de/aspose.slides.export/itiffoptions/pixel_format/) | Gibt das Pixel-Format für die erzeugten Bilder an.<br/>            Lesen/Schreiben [`ImagePixelFormat`](/slides/python-net/de/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/de/aspose.slides.export/itiffoptions/slides_layout_options/) | Liest oder setzt den Modus, in dem Folien beim Export einer Präsentation [`ISlidesLayoutOptions`](/slides/python-net/de/aspose.slides.export/islideslayoutoptions) auf die Seite gelegt werden. |
| [`bw_conversion_mode`](/slides/python-net/de/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Gibt den Algorithmus zum Konvertieren eines Farbbildes in ein Schwarz-weiß-Bild an.<br/>            Diese Option wird nur angewendet, wenn [`ITiffOptions.compression_type`](/slides/python-net/de/aspose.slides.export/itiffoptions/compression_type) <br/>            auf [`TiffCompressionTypes.CCITT4`](/slides/python-net/de/aspose.slides.export/tiffcompressiontypes/CCITT4) oder [`TiffCompressionTypes.CCITT3`](/slides/python-net/de/aspose.slides.export/tiffcompressiontypes/CCITT3) gesetzt ist<br/>            Lesen/Schreiben [`BlackWhiteConversionMode`](/slides/python-net/de/aspose.slides.export/blackwhiteconversionmode).<br/>            Standard ist [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/de/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/de/aspose.slides.export/itiffoptions/ink_options/) | Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern.<br/>            Nur lesen [`IInkOptions`](/slides/python-net/de/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Siehe auch
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)