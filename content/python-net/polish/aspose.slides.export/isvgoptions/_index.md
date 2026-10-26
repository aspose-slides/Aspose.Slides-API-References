---
title: ISVGOptions class
second_title: Aspose.Slides dla Pythona via .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.export/isvgoptions/
---
## ISVGOptions klasa

Reprezentuje opcje SVG.

Typ ISVGOptions udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`vectorize_text`](/slides/python-net/pl/aspose.slides.export/isvgoptions/vectorize_text/) | Określa, czy tekst na slajdzie zostanie zapisany jako grafika.<br/>            Odczyt/zapis **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/pl/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Zwraca lub ustawia dolny limit rozdzielczości dla rasteryzacji metapliku.<br/>            Odczyt/zapis **int**. |
| [`disable_3d_text`](/slides/python-net/pl/aspose.slides.export/isvgoptions/disable_3d_text/) | Określa, czy tekst 3D jest wyłączony w SVG.<br/>            Odczyt/zapis **bool**. |
| [`disable_gradient_split`](/slides/python-net/pl/aspose.slides.export/isvgoptions/disable_gradient_split/) | Wyłącza podział gradientów FromCornerX i FromCenter.<br/>            Odczyt/zapis **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/pl/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 nie umożliwia definiowania wcięć dla znaczników.<br/>            Silnik zapisu SVG Aspose.Slides posiada obejście tego problemu:<br/>            przycina koniec linii z strzałką, tak aby linia nie nakładała się na znaczniki.<br/>            Ta opcja wyłącza takie zachowanie.<br/>            Odczyt/zapis **bool**. |
| [`jpeg_quality`](/slides/python-net/pl/aspose.slides.export/isvgoptions/jpeg_quality/) | Określa jakość kodowania JPEG.<br/>            Odczyt/zapis **int**. |
| [`shape_formatting_controller`](/slides/python-net/pl/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Zwraca i ustawia interfejs wywołania zwrotnego, który umożliwia użytkownikowi kontrolowanie konwersji kształtów.<br/>            Odczyt/zapis [`ISvgShapeFormattingController`](/slides/python-net/pl/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/pl/aspose.slides.export/isvgoptions/pictures_compression/) | Reprezentuje poziom kompresji obrazów<br/>            Odczyt/zapis [`ISVGOptions.pictures_compression`](/slides/python-net/pl/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/pl/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli true, przycięte<br/>            części zostaną usunięte, jeśli false, zostaną zserializowane w dokumencie (co może potencjalnie prowadzić do<br/>            większego pliku)<br/>            Odczyt/zapis **bool**. |
| [`use_frame_size`](/slides/python-net/pl/aspose.slides.export/isvgoptions/use_frame_size/) | Określa, czy ramka tekstowa zostanie uwzględniona w obszarze renderowania, czy nie.<br/>            Odczyt/zapis **bool**.<br/>            Wartość domyślna to false. |
| [`use_frame_rotation`](/slides/python-net/pl/aspose.slides.export/isvgoptions/use_frame_rotation/) | Określa, czy wykonać określony obrót kształtu podczas renderowania, czy nie.<br/>            Odczyt/zapis **bool**.<br/>            Wartość domyślna to true. |
| [`external_fonts_handling`](/slides/python-net/pl/aspose.slides.export/isvgoptions/external_fonts_handling/) | Określa sposób obsługi zewnętrznie ładowanych czcionek.<br/>            Odczyt/zapis [`SvgExternalFontsHandling`](/slides/python-net/pl/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/pl/aspose.slides.export/isvgoptions/ink_options/) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie.<br/>            Tylko do odczytu [`IInkOptions`](/slides/python-net/pl/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/pl/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Pobiera lub ustawia wartość określającą, czy tekst jest renderowany bez użycia ligatur.<br/>            Gdy ustawione na `true`, ligatury będą wyłączone w renderowanym wyniku. Domyślnie ta właściwość ma wartość `false`. |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Zobacz także
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)