---
title: PdfOptions class
second_title: Aspose.Slides dla Pythona poprzez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.export/pdfoptions/
---
## Klasa PdfOptions

Udostępnia opcje, które kontrolują sposób zapisywania prezentacji w formacie Pdf.

**Dziedziczenie:**[`PdfOptions`](/slides/python-net/pl/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)

Typ PdfOptions udostępnia następujące elementy:

## Konstruktorzy

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.export/pdfoptions/__init__/#) | Domyślny konstruktor. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/pdfoptions/warning_callback/) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany.<br/>            Odczyt/zapis [`IWarningCallback`](/slides/python-net/pl/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/pdfoptions/progress_callback/) | Reprezentuje obiekt zwrotny dla aktualizacji postępu zapisu w procentach.<br/>            Zobacz [`IProgressCallback`](/slides/python-net/pl/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/pdfoptions/default_regular_font/) | Zwraca lub ustawia czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa.<br/>            Odczyt/zapis **str**. |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/pdfoptions/gradient_style/) | Zwraca lub ustawia styl wizualny gradientu.<br/>            Odczyt/zapis [`GradientStyle`](/slides/python-net/pl/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/pdfoptions/skip_java_script_links/) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji.<br/>            Odczyt/zapis **bool**. Domyślna wartość to **false**. |
| [`slides_layout_options`](/slides/python-net/pl/aspose.slides.export/pdfoptions/slides_layout_options/) | Zwraca lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [`ISlidesLayoutOptions`](/slides/python-net/pl/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/pl/aspose.slides.export/pdfoptions/ink_options/) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie.<br/>            Tylko do odczytu [`IInkOptions`](/slides/python-net/pl/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/pl/aspose.slides.export/pdfoptions/show_hidden_slides/) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy.<br/>            Domyślna wartość to `false`. |
| [`text_compression`](/slides/python-net/pl/aspose.slides.export/pdfoptions/text_compression/) | Określa typ kompresji używany dla całej treści tekstowej w dokumencie.<br/>            Odczyt/zapis [`PdfTextCompression`](/slides/python-net/pl/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/pl/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Wskazuje, czy dla każdego obrazu ma być automatycznie wybierana najskuteczniejsza kompresja (zamiast domyślnej).<br/>            Jeśli ustawiono na **bool**.true, dla każdego obrazu w prezentacji zostanie wybrany najbardziej odpowiedni algorytm kompresji, co spowoduje mniejszy rozmiar wynikowego dokumentu PDF.<br/>            Wybranie najlepszego współczynnika kompresji obrazu jest obliczeniowo kosztowne i wymaga dodatkowej pamięci RAM, a domyślną wartością tego ustawienia jest **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/pl/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Określa, czy Aspose.Slides osadzi wspólne czcionki dla tekstu ASCII (zakres kodów 33..127).<br/>            Czcionki dla kodów znaków większych niż 127 są zawsze osadzane.<br/>            Lista wspólnych czcionek obejmuje podstawowe 14 czcionek PDF oraz dodatkowe czcionki określone przez użytkownika.<br/>            Odczyt/zapis **bool**. |
| [`additional_common_font_families`](/slides/python-net/pl/aspose.slides.export/pdfoptions/additional_common_font_families/) | Zwraca lub ustawia tablicę nazw rodzin czcionek definiowanych przez użytkownika, które Aspose.Slides powinien uznać za wspólne.<br/>            Odczyt/zapis **str**[]. |
| [`embed_full_fonts`](/slides/python-net/pl/aspose.slides.export/pdfoptions/embed_full_fonts/) | Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko używany podzbiór.<br/>            Odczyt/zapis **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/pl/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Wskazuje, czy tekst powinien być rastrowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje stylu pogrubionego.<br/>            Takie podejście może poprawić jakość tekstu w wynikowym PDF dla niektórych czcionek.<br/>            Odczyt/zapis **bool**. |
| [`jpeg_quality`](/slides/python-net/pl/aspose.slides.export/pdfoptions/jpeg_quality/) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF.<br/>            Odczyt/zapis **int**. |
| [`compliance`](/slides/python-net/pl/aspose.slides.export/pdfoptions/compliance/) | Pożądany poziom zgodności wygenerowanego dokumentu PDF.<br/>            Odczyt/zapis [`PdfCompliance`](/slides/python-net/pl/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/pl/aspose.slides.export/pdfoptions/password/) | Ustawienie hasła użytkownika w celu ochrony dokumentu PDF.<br/>            Odczyt/zapis **str**. |
| [`access_permissions`](/slides/python-net/pl/aspose.slides.export/pdfoptions/access_permissions/) | Zawiera zestaw flag określających, które uprawnienia dostępu mają być przyznane przy otwieraniu dokumentu z dostępem użytkownika.<br/>            Zobacz [`PdfAccessPermissions`](/slides/python-net/pl/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/pl/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | Ustaw na true, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG.<br/>            Odczyt/zapis **bool**. |
| [`sufficient_resolution`](/slides/python-net/pl/aspose.slides.export/pdfoptions/sufficient_resolution/) | Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF.<br/>            <br/>Właściwość wpływa na rozmiar pliku, czas eksportu i jakość obrazu.<br/><br/><br/>Domyślna wartość to **96**.<br/><br/><br/>            Odczyt/zapis **float**. |
| [`draw_slides_frame`](/slides/python-net/pl/aspose.slides.export/pdfoptions/draw_slides_frame/) | Ustaw na true, aby rysować czarną ramkę wokół każdego slajdu.<br/>            Odczyt/zapis **bool**. |
| [`image_transparent_color`](/slides/python-net/pl/aspose.slides.export/pdfoptions/image_transparent_color/) | Zwraca lub ustawia przezroczysty kolor obrazu. |
| [`apply_image_transparent`](/slides/python-net/pl/aspose.slides.export/pdfoptions/apply_image_transparent/) | Stosuje określony przezroczysty kolor do obrazu, jeśli `true`. |
| [`include_ole_data`](/slides/python-net/pl/aspose.slides.export/pdfoptions/include_ole_data/) | Ustaw na true, aby konwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF.<br/>            Odczyt/zapis **bool**. |

### Zobacz także
* klasa [`PdfOptions`](/slides/python-net/pl/aspose.slides.export/pdfoptions)
* klasa [`SaveOptions`](/slides/python-net/pl/aspose.slides.export/saveoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)