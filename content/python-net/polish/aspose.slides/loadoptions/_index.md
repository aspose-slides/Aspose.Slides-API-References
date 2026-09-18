---
title: LoadOptions class
second_title: Aspose.Slides dla Pythona via .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/loadoptions/
---
## LoadOptions klasa

Umożliwia określenie dodatkowych opcji (takich jak format lub domyślna czcionka) podczas ładowania prezentacji.

Typ LoadOptions udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides/loadoptions/__init__/#) | Tworzy nowe domyślne opcje ładowania. |
| [`__init__(self, load_format)`](/slides/python-net/pl/aspose.slides/loadoptions/__init__/#loadformat) | Tworzy nowe opcje ładowania. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`load_format`](/slides/python-net/pl/aspose.slides/loadoptions/load_format/) | Zwraca lub ustawia format prezentacji do załadowania.<br/>            Odczyt/zapis [`LoadFormat`](/slides/python-net/pl/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides/loadoptions/default_regular_font/) | Zwraca lub ustawia standardową czcionkę używaną, gdy nie znaleziono czcionki źródłowej.<br/>            Odczyt/zapis **str**. |
| [`default_symbol_font`](/slides/python-net/pl/aspose.slides/loadoptions/default_symbol_font/) | Zwraca lub ustawia czcionkę Symbol używaną, gdy nie znaleziono czcionki źródłowej.<br/>            Odczyt/zapis **str**. |
| [`default_asian_font`](/slides/python-net/pl/aspose.slides/loadoptions/default_asian_font/) | Zwraca lub ustawia czcionkę azjatycką używaną, gdy nie znaleziono czcionki źródłowej.<br/>            Odczyt/zapis **str**. |
| [`password`](/slides/python-net/pl/aspose.slides/loadoptions/password/) | Pobiera lub ustawia hasło.<br/>            Odczyt/zapis **str**. |
| [`only_load_document_properties`](/slides/python-net/pl/aspose.slides/loadoptions/only_load_document_properties/) | To właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem.<br/>            Wartość true oznacza, że z zaszyfrowanego pliku prezentacji należy załadować tylko właściwości dokumentu i hasło ma być ignorowane.<br/>            Wartość false oznacza, że cała zaszyfrowana prezentacja musi być załadowana przy użyciu właściwego hasła.<br/>            Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana.<br/>            Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, wtedy właściwości dokumentu nie mogą być załadowane i zostanie zgłoszony wyjątek.<br/>            Odczyt/zapis **bool**. |
| [`warning_callback`](/slides/python-net/pl/aspose.slides/loadoptions/warning_callback/) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania <br/>            będzie kontynuowany czy zostanie przerwany.<br/>            Odczyt/zapis [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/pl/aspose.slides/loadoptions/blob_management_options/) | Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi Binary Large Objects (BLOBs),<br/>            takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. Opcje te mają na celu ustalenie<br/>            najlepszego stosunku wydajności do zużycia pamięci dla konkretnego środowiska lub wymagań.<br/>            Binary Large Object (BLOB) to dane binarne przechowywane jako pojedynczy byt – np. BLOB może <br/>            być dźwiękiem, wideo lub samą prezentacją. |
| [`document_level_font_sources`](/slides/python-net/pl/aspose.slides/loadoptions/document_level_font_sources/) | Określa źródła zewnętrznych czcionek używanych przez prezentację.<br/>            Czcionki te są dostępne dla prezentacji przez cały jej okres życia i nie są współdzielone z innymi prezentacjami |
| [`interruption_token`](/slides/python-net/pl/aspose.slides/loadoptions/interruption_token/) | Token służący do monitorowania żądań przerwania.<br/>            <br/>            Token ten zarządza całym okresem życia instancji [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). Każda długotrwała operacja, taka jak ładowanie <br/>            lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [`InterruptionTokenSource.interrupt`](/slides/python-net/pl/aspose.slides/interruptiontokensource/interrupt) z <br/>            obiektu [`InterruptionTokenSource`](/slides/python-net/pl/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/pl/aspose.slides/loadoptions/resource_loading_callback/) | Zwraca lub ustawia interfejs zwrotny, który zarządza ładowaniem zasobów zewnętrznych.<br/>            Odczyt/zapis [`IResourceLoadingCallback`](/slides/python-net/pl/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/pl/aspose.slides/loadoptions/spreadsheet_options/) | Pobiera opcje dla arkuszy kalkulacyjnych. Na przykład te opcje wpływają na obliczanie formuł dla wykresów. |
| [`default_text_language`](/slides/python-net/pl/aspose.slides/loadoptions/default_text_language/) | Zwraca lub ustawia domyślny język tekstu w prezentacji.<br/>             Odczyt/zapis **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/pl/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.<br/>            <br/>Typy osadzonych obiektów binarnych:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/pl/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/pl/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/pl/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Odczyt/zapis **bool**. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)