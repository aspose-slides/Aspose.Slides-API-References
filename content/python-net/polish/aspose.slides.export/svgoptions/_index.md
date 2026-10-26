---
title: SVGOptions class
second_title: Aspose.Slides dla Pythona przez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.export/svgoptions/
---
## Klasa SVGOptions

Reprezentuje opcje SVG.

**Dziedziczenie:**[`SVGOptions`](/slides/python-net/pl/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)

Typ SVGOptions udostępnia następujące członki:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.export/svgoptions/__init__/#) | Inicjalizuje nową instancję klasy SVGOptions. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/pl/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Inicjalizuje nową instancję klasy SVGOptions określając obiekt kontrolera osadzania odnośników. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/svgoptions/warning_callback/) | Zwraca lub ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany.<br/>            Odczyt/zapis [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/svgoptions/progress_callback/) | Reprezentuje obiekt wywołania zwrotnego do aktualizacji postępu zapisu w procentach.<br/>            Zobacz [`IProgressCallback`](/slides/python-net/pl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/svgoptions/default_regular_font/) | Zwraca lub ustawia czcionkę używaną w przypadku, gdy nie znaleziono czcionki źródłowej.<br/>            Odczyt/zapis **str**. |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/svgoptions/gradient_style/) | Zwraca lub ustawia styl wizualny gradientu.<br/>            Odczyt/zapis [`GradientStyle`](/slides/python-net/pl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/svgoptions/skip_java_script_links/) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji.<br/>            Odczyt/zapis **bool**. Wartość domyślna to **false**. |
| [`ink_options`](/slides/python-net/pl/aspose.slides.export/svgoptions/ink_options/) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie.<br/>            Tylko do odczytu [`IInkOptions`](/slides/python-net/pl/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/pl/aspose.slides.export/svgoptions/use_frame_size/) | Określa, czy ramka tekstowa ma być uwzględniona w obszarze renderowania.<br/>            Odczyt/zapis **bool**.<br/>            Wartość domyślna to false. |
| [`use_frame_rotation`](/slides/python-net/pl/aspose.slides.export/svgoptions/use_frame_rotation/) | Określa, czy wykonać określony obrót kształtu podczas renderowania.<br/>            Odczyt/zapis **bool**.<br/>            Wartość domyślna to true. |
| [`vectorize_text`](/slides/python-net/pl/aspose.slides.export/svgoptions/vectorize_text/) | Określa, czy tekst na slajdzie zostanie zapisany jako grafika.<br/>            Odczyt/zapis **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/pl/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Zwraca lub ustawia dolny limit rozdzielczości dla rasteryzacji metafili.<br/>            Odczyt/zapis **int**. |
| [`disable_3d_text`](/slides/python-net/pl/aspose.slides.export/svgoptions/disable_3d_text/) | Określa, czy tekst 3D jest wyłączony w SVG.<br/>            Odczyt/zapis **bool**. |
| [`disable_gradient_split`](/slides/python-net/pl/aspose.slides.export/svgoptions/disable_gradient_split/) | Wyłącza dzielenie gradientów FromCornerX i FromCenter.<br/>            Odczyt/zapis **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/pl/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 nie umożliwia definiowania wcięć dla znaczników.<br/>            Silnik zapisu SVG Aspose.Slides ma obejście tego problemu:<br/>            przycina koniec linii z strzałką, aby linia nie nachodziła na znaczniki.<br/>            Ta opcja wyłącza takie zachowanie.<br/>            Odczyt/zapis **bool**. |
| [`default`](/slides/python-net/pl/aspose.slides.export/svgoptions/default/) | Zwraca ustawienia domyślne.<br/>            Tylko do odczytu [`SVGOptions`](/slides/python-net/pl/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/pl/aspose.slides.export/svgoptions/simple/) | Zwraca ustawienia dla najprostszego i najmniejszego generowania pliku SVG.<br/>            Tylko do odczytu [`SVGOptions`](/slides/python-net/pl/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/pl/aspose.slides.export/svgoptions/wysiwyg/) | Zwraca ustawienia dla najbardziej dokładnego generowania pliku SVG.<br/>            Tylko do odczytu [`SVGOptions`](/slides/python-net/pl/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/pl/aspose.slides.export/svgoptions/jpeg_quality/) | Określa jakość kodowania JPEG.<br/>            Odczyt/zapis **int**. |
| [`shape_formatting_controller`](/slides/python-net/pl/aspose.slides.export/svgoptions/shape_formatting_controller/) | Zwraca i ustawia interfejs wywołania zwrotnego, który umożliwia użytkownikowi kontrolowanie konwersji kształtów.<br/>            Odczyt/zapis [`ISvgShapeFormattingController`](/slides/python-net/pl/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/pl/aspose.slides.export/svgoptions/pictures_compression/) | Reprezentuje poziom kompresji obrazów |
| [`delete_pictures_cropped_areas`](/slides/python-net/pl/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Flaga logiczna wskazuje, czy przycięte części pozostają jako część dokumentu. Jeśli true, przycięte<br/>            części zostaną usunięte, jeśli false, zostaną zserializowane w dokumencie (co może potencjalnie prowadzić do<br/>            większego pliku) |
| [`external_fonts_handling`](/slides/python-net/pl/aspose.slides.export/svgoptions/external_fonts_handling/) | Określa sposób obsługi zewnętrznie ładowanych czcionek.<br/>            Odczyt/zapis [`SvgExternalFontsHandling`](/slides/python-net/pl/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/pl/aspose.slides.export/svgoptions/disable_font_ligatures/) | Zwraca lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur.<br/>            Gdy ustawione na `true`, ligatury będą wyłączone w wyjściu renderowanym. Domyślnie, ta właściwość jest ustawiona na `false`. |

### Zobacz także
* klasa [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)
* klasa [`SVGOptions`](/slides/python-net/pl/aspose.slides.export/svgoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)