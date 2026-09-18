---
title: IPdfOptions class
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.export/ipdfoptions/
---
## IPdfOptions klasa

Udostępnia opcje, które kontrolują, jak prezentacja jest zapisywana w formacie Pdf.

Typ IPdfOptions udostępnia następujące członki:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`text_compression`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/text_compression/) | Określa typ kompresji używany dla całej treści tekstowej w dokumencie.<br/>            Odczyt/zapis [`PdfTextCompression`](/slides/python-net/pl/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Wskazuje, czy najskuteczniejsza kompresja (zamiast domyślnej) dla każdego obrazu ma być wybierana <br/>            automatycznie. Jeśli ustawiono na **bool**.true, dla każdego obrazu w prezentacji zostanie wybrany najbardziej odpowiedni algorytm kompresji, co doprowadzi do mniejszego rozmiaru wygenerowanego dokumentu PDF. <br/>            Wybór najlepszego współczynnika kompresji obrazu jest kosztowny obliczeniowo i wymaga dodatkowej pamięci RAM, a to ustawienie jest domyślnie **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | Prawda, aby osadzić czcionki TrueType dla znaków ASCII 32-127.<br/>            Czcionki dla kodów znaków większych niż 127 są zawsze osadzane.<br/>            Odczyt/zapis **bool**. |
| [`show_hidden_slides`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy.<br/>            Domyślnie ``false``. |
| [`additional_common_font_families`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Zwraca lub ustawia tablicę nazw rodzin czcionek definiowanych przez użytkownika, które Aspose.Slides powinien uznać za wspólne.<br/>            Odczyt/zapis **str**[]. |
| [`embed_full_fonts`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko używany podzbiór.<br/>            Odczyt/zapis **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Wskazuje, czy tekst ma być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia.<br/>            To podejście może poprawić jakość tekstu w wyniku PDF dla niektórych czcionek.<br/>            Odczyt/zapis **bool**. |
| [`jpeg_quality`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/jpeg_quality/) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF.<br/>            Odczyt/zapis **int**. |
| [`compliance`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/compliance/) | Pożądany poziom zgodności dla wygenerowanego dokumentu PDF.<br/>            Odczyt/zapis [`PdfCompliance`](/slides/python-net/pl/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/password/) | Ustawienie hasła użytkownika w celu ochrony dokumentu PDF. <br/>            Odczyt/zapis **str**. |
| [`access_permissions`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/access_permissions/) | Zawiera zestaw flag określających, które uprawnienia dostępu mają być przyznane przy otwieraniu dokumentu<br/>            z dostępem użytkownika. Zobacz [`PdfAccessPermissions`](/slides/python-net/pl/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | Prawda, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG.<br/>            Odczyt/zapis **bool**. |
| [`sufficient_resolution`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF.<br/>            <br/>Właściwość wpływa na rozmiar pliku, czas eksportu i jakość obrazu.<br/><br/><br/>Domyślna wartość to **96** .<br/><br/><br/>            Odczyt/zapis **float**. |
| [`draw_slides_frame`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/draw_slides_frame/) | Prawda, aby narysować czarną ramkę wokół każdego slajdu.<br/>             Odczyt/zapis **bool**. |
| [`slides_layout_options`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/slides_layout_options/) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [`ISlidesLayoutOptions`](/slides/python-net/pl/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/image_transparent_color/) | Pobiera lub ustawia przezroczysty kolor obrazu. |
| [`apply_image_transparent`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Zastosowuje określony przezroczysty kolor do obrazu, jeśli `true`. |
| [`ink_options`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/ink_options/) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie.<br/>            Tylko do odczytu [`IInkOptions`](/slides/python-net/pl/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/include_ole_data/) | Prawda, aby konwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF.<br/>            Odczyt/zapis **bool**. |
| [`warning_callback`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/pl/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### Zobacz także
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)