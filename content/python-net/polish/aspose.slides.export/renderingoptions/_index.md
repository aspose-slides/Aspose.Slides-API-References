---
title: RenderingOptions class
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.export/renderingoptions/
---
## RenderingOptions klasa

Provides options that control how a presentation/slide is rendered.

**Dziedziczenie:**[`RenderingOptions`](/slides/python-net/pl/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)

The RenderingOptions type exposes the following members:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.export/renderingoptions/__init__/#) | Default constructor. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/renderingoptions/warning_callback/) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany.<br/>            Odczyt/zapis [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/renderingoptions/progress_callback/) | Reprezentuje obiekt wywołania zwrotnego dla aktualizacji postępu zapisywania w procentach.<br/>            Zobacz [`IProgressCallback`](/slides/python-net/pl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/renderingoptions/default_regular_font/) | Zwraca lub ustawia czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa.<br/>            Odczyt-zapis **str**. |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/renderingoptions/gradient_style/) | Zwraca lub ustawia styl wizualny gradientu.<br/>            Odczyt/zapis [`GradientStyle`](/slides/python-net/pl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/renderingoptions/skip_java_script_links/) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji.<br/>            Odczyt/zapis **bool**. Domyślna wartość to **false**. |
| [`slides_layout_options`](/slides/python-net/pl/aspose.slides.export/renderingoptions/slides_layout_options/) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie przy eksportowaniu prezentacji [`ISlidesLayoutOptions`](/slides/python-net/pl/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/pl/aspose.slides.export/renderingoptions/ink_options/) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie.<br/>            Tylko do odczytu [`IInkOptions`](/slides/python-net/pl/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/pl/aspose.slides.export/renderingoptions/disable_font_ligatures/) | Pobiera lub ustawia wartość określającą, czy tekst jest renderowany bez użycia ligatur.<br/>            Gdy ustawione na `true`, ligatury będą wyłączone w renderowanym wyniku. Domyślnie ta właściwość jest ustawiona na `false`. |


### Zobacz także
* klasa [`RenderingOptions`](/slides/python-net/pl/aspose.slides.export/renderingoptions)
* klasa [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)