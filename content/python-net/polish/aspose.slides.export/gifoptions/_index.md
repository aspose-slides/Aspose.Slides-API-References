---
title: GifOptions class
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.export/gifoptions/
---
## GifOptions klasa

Reprezentuje opcje eksportu GIF.

**Dziedziczenie:**[`GifOptions`](/slides/python-net/pl/aspose.slides.export/gifoptions) → [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)

Typ GifOptions udostępnia następujących członków:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.export/gifoptions/__init__/#) | Inicjalizuje nową instancję klasy GifOptions. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/gifoptions/warning_callback/) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany.<br/>            Odczyt/zapis [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/gifoptions/progress_callback/) | Reprezentuje obiekt wywołania zwrotnego do zapisywania aktualizacji postępu w procentach.<br/>            Zobacz [`IProgressCallback`](/slides/python-net/pl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/gifoptions/default_regular_font/) | Zwraca lub ustawia czcionkę używaną w przypadku, gdy nie zostanie znaleziona czcionka źródłowa.<br/>            Odczyt/zapis **str**. |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/gifoptions/gradient_style/) | Zwraca lub ustawia styl wizualny gradientu.<br/>            Odczyt/zapis [`GradientStyle`](/slides/python-net/pl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/gifoptions/skip_java_script_links/) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. <br/>            Odczyt/zapis **bool**. Domyślna wartość to **false**. |
| [`frame_size`](/slides/python-net/pl/aspose.slides.export/gifoptions/frame_size/) | Zwraca lub ustawia rozmiar klatki. |
| [`export_hidden_slides`](/slides/python-net/pl/aspose.slides.export/gifoptions/export_hidden_slides/) | Określa, czy ukryte slajdy będą eksportowane.<br/>            Domyślna wartość to false. |
| [`transition_fps`](/slides/python-net/pl/aspose.slides.export/gifoptions/transition_fps/) | Zwraca lub ustawia FPS przejścia [klatki/sek]<br/>            Domyślna wartość to 25. |
| [`default_delay`](/slides/python-net/pl/aspose.slides.export/gifoptions/default_delay/) | Zwraca lub ustawia domyślny czas opóźnienia [ms]. Ta wartość będzie użyta, jeśli [`ISlideShowTransition.advance_after_time`](/slides/python-net/pl/aspose.slides/islideshowtransition/advance_after_time) nie jest ustawione.<br/>            Domyślna wartość to 1000. |

### Zobacz także
* klasa [`GifOptions`](/slides/python-net/pl/aspose.slides.export/gifoptions)
* klasa [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)