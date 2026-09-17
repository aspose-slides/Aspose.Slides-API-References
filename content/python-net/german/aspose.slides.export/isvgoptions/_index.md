---
title: ISVGOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/isvgoptions/
---
## ISVGOptions Klasse

Represents an SVG options.

The ISVGOptions type exposes the following members:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`vectorize_text`](/slides/python-net/de/aspose.slides.export/isvgoptions/vectorize_text/) | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird.<br/>            Lesen/Schreiben **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/de/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Gibt die untere Auflösungsgrenze für die Rasterisierung von Metadateien zurück oder legt sie fest.<br/>            Lesen/Schreiben **int**. |
| [`disable_3d_text`](/slides/python-net/de/aspose.slides.export/isvgoptions/disable_3d_text/) | Bestimmt, ob der 3D-Text in SVG deaktiviert ist.<br/>            Lesen/Schreiben **bool**. |
| [`disable_gradient_split`](/slides/python-net/de/aspose.slides.export/isvgoptions/disable_gradient_split/) | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen.<br/>            Lesen/Schreiben **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/de/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 kann keine Einrückungen für Marker definieren.<br/>            Die SVG-Schreibengine von Aspose.Slides hat einen Workaround für dieses Problem:<br/>            Sie schneidet das Linienende mit Pfeil ab, sodass die Linie nicht mit Markern überlappt.<br/>            Diese Option schaltet dieses Verhalten aus.<br/>            Lesen/Schreiben **bool**. |
| [`jpeg_quality`](/slides/python-net/de/aspose.slides.export/isvgoptions/jpeg_quality/) | Bestimmt die JPEG-Kodierungsqualität.<br/>            Lesen/Schreiben **int**. |
| [`shape_formatting_controller`](/slides/python-net/de/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Gibt eine Callback-Schnittstelle zurück und legt sie fest, die dem Benutzer die Kontrolle über die Formkonvertierung ermöglicht.<br/>            Lesen/Schreiben [`ISvgShapeFormattingController`](/slides/python-net/de/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/de/aspose.slides.export/isvgoptions/pictures_compression/) | Stellt das Kompressionsniveau der Bilder dar<br/>            Lesen/Schreiben [`ISVGOptions.pictures_compression`](/slides/python-net/de/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/de/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Ein boolesches Flag gibt an, ob die zugeschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die zugeschnittenen<br/>            Teile entfernt, wenn false, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann)<br/>            Lesen/Schreiben **bool**. |
| [`use_frame_size`](/slides/python-net/de/aspose.slides.export/isvgoptions/use_frame_size/) | Bestimmt, ob der Textrahmen in einen Rendering-Bereich einbezogen wird oder nicht.<br/>            Lesen/Schreiben **bool**.<br/>            Standardwert ist false. |
| [`use_frame_rotation`](/slides/python-net/de/aspose.slides.export/isvgoptions/use_frame_rotation/) | Bestimmt, ob die angegebene Drehung der Form beim Rendern ausgeführt wird oder nicht.<br/>            Lesen/Schreiben **bool**.<br/>            Standardwert ist true. |
| [`external_fonts_handling`](/slides/python-net/de/aspose.slides.export/isvgoptions/external_fonts_handling/) | Bestimmt, wie extern geladene Schriftarten gehandhabt werden.<br/>            Lesen/Schreiben [`SvgExternalFontsHandling`](/slides/python-net/de/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/de/aspose.slides.export/isvgoptions/ink_options/) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern.<br/>            Nur-Lesen [`IInkOptions`](/slides/python-net/de/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/de/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Erhält oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird.<br/>            Wenn der Wert auf `true` gesetzt ist, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf `false` gesetzt. |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Siehe auch
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)