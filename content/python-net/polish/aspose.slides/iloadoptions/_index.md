---
title: ILoadOptions class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/iloadoptions/
---
## ILoadOptions klasa

Umożliwia określenie dodatkowych opcji (takich jak format lub domyślna czcionka) podczas ładowania prezentacji.

Typ ILoadOptions udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`load_format`](/slides/python-net/pl/aspose.slides/iloadoptions/load_format/) | Zwraca lub ustawia format prezentacji do załadowania.<br/>            Read/write [`LoadFormat`](/slides/python-net/pl/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides/iloadoptions/default_regular_font/) | Zwraca lub ustawia czcionkę Regular używaną w przypadku, gdy nie znaleziono czcionki źródłowej.<br/>            Read-write **str**. |
| [`default_symbol_font`](/slides/python-net/pl/aspose.slides/iloadoptions/default_symbol_font/) | Zwraca lub ustawia czcionkę Symbol używaną w przypadku, gdy nie znaleziono czcionki źródłowej.<br/>            Read-write **str**. |
| [`default_asian_font`](/slides/python-net/pl/aspose.slides/iloadoptions/default_asian_font/) | Zwraca lub ustawia czcionkę Asian używaną w przypadku, gdy nie znaleziono czcionki źródłowej.<br/>            Read-write **str**. |
| [`password`](/slides/python-net/pl/aspose.slides/iloadoptions/password/) | Zwraca lub ustawia hasło.<br/>            Read-write **str**. |
| [`only_load_document_properties`](/slides/python-net/pl/aspose.slides/iloadoptions/only_load_document_properties/) | Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem.<br/>            Wartość true oznacza, że z zaszyfrowanego pliku prezentacji należy wczytać tylko właściwości dokumentu i hasło ma być pominięte.<br/>            Wartość false oznacza, że cała zaszyfrowana prezentacja musi być wczytana przy użyciu prawidłowego hasła.<br/>            Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana.<br/>            Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, to<br/>            właściwości dokumentu nie mogą być wczytane i zostanie rzucony wyjątek.<br/>            Read-write **bool**. |
| [`warning_callback`](/slides/python-net/pl/aspose.slides/iloadoptions/warning_callback/) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania <br/>            będzie kontynuowany, czy zostanie przerwany.<br/>            Read/write [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/pl/aspose.slides/iloadoptions/blob_management_options/) | Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi Binary Large Objects (BLOBs),<br/>            takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. Opcje te mają na celu ustawienie<br/>            optymalnego stosunku wydajności do zużycia pamięci dla konkretnego środowiska lub wymagań.<br/>            Binary Large Object (BLOB) to dane binarne przechowywane jako pojedynczy podmiot — np. BLOB może być<br/>            dźwiękiem, wideo lub samą prezentacją. |
| [`document_level_font_sources`](/slides/python-net/pl/aspose.slides/iloadoptions/document_level_font_sources/) | Określa źródła zewnętrznych czcionek używanych przez prezentację.<br/>            Czcionki te są dostępne dla prezentacji przez cały jej czas życia i nie są współdzielone z innymi prezentacjami |
| [`interruption_token`](/slides/python-net/pl/aspose.slides/iloadoptions/interruption_token/) | Token do monitorowania żądań przerwania.<br/>            <br/>            Token ten zarządza całym okresem życia instancji [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). Każda długotrwała operacja, taka jak ładowanie <br/>            lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [`IInterruptionTokenSource.interrupt`](/slides/python-net/pl/aspose.slides/iinterruptiontokensource/interrupt) z <br/>            [`IInterruptionTokenSource`](/slides/python-net/pl/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/pl/aspose.slides/iloadoptions/resource_loading_callback/) | Zwraca lub ustawia interfejs zwrotny, który zarządza ładowaniem zasobów zewnętrznych.<br/>            Read/write [`IResourceLoadingCallback`](/slides/python-net/pl/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/pl/aspose.slides/iloadoptions/spreadsheet_options/) | Reprezentuje opcje, które mogą być użyte do określenia dodatkowego zachowania arkuszy kalkulacyjnych. |
| [`default_text_language`](/slides/python-net/pl/aspose.slides/iloadoptions/default_text_language/) | Zwraca lub ustawia domyślny język tekstu prezentacji.<br/>             Read/write **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/pl/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Określa, czy Aspose.Slides usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji.<br/>            <br/>Typy osadzonych obiektów binarnych:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/pl/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/pl/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/pl/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Read/write **bool**. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)