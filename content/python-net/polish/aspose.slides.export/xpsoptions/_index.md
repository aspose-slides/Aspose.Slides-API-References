---
title: XpsOptions class
second_title: Aspose.Slides dla Pythona poprzez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.export/xpsoptions/
---
## XpsOptions klasa

Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie XPS.

**Dziedziczenie:**[`XpsOptions`](/slides/python-net/pl/aspose.slides.export/xpsoptions) → [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)

Typ XpsOptions udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.export/xpsoptions/__init__/#) | Domyślny konstruktor. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/xpsoptions/warning_callback/) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany.<br/>            Odczyt/zapis [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/xpsoptions/progress_callback/) | Reprezentuje obiekt wywołania zwrotnego dla aktualizacji postępu zapisu w procentach.<br/>            Zobacz [`IProgressCallback`](/slides/python-net/pl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/xpsoptions/default_regular_font/) | Zwraca lub ustawia czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa.<br/>            Odczyt-zapis **str**. |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/xpsoptions/gradient_style/) | Zwraca lub ustawia styl wizualny gradientu.<br/>            Odczyt/zapis [`GradientStyle`](/slides/python-net/pl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/xpsoptions/skip_java_script_links/) | Określa, czy pomijać odnośniki hipertekstowe z wywołaniami JavaScript podczas zapisywania prezentacji.<br/>            Odczyt/zapis **bool**. Domyślna wartość to **false**. |
| [`show_hidden_slides`](/slides/python-net/pl/aspose.slides.export/xpsoptions/show_hidden_slides/) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie.<br/>            Domyślna wartość to `false`. |
| [`save_metafiles_as_png`](/slides/python-net/pl/aspose.slides.export/xpsoptions/save_metafiles_as_png/) | True, aby przekonwertować wszystkie pliki metafile używane w prezentacji na obrazy PNG.<br/>            Odczyt/zapis **bool**. |
| [`draw_slides_frame`](/slides/python-net/pl/aspose.slides.export/xpsoptions/draw_slides_frame/) | True, aby narysować czarną ramkę wokół każdego slajdu.<br/>            Odczyt/zapis **bool**. |

### Zobacz także
* klasa [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)
* klasa [`XpsOptions`](/slides/python-net/pl/aspose.slides.export/xpsoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)