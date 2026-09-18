---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides dla Pythona przez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.export/embedallfontshtmlcontroller/
---
## Klasa EmbedAllFontsHtmlController

Klasa kontrolera formatowania używana do osadzania wszystkich czcionek prezentacji w formacie WOFF.

Typ EmbedAllFontsHtmlController udostępnia następujące członków:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Tworzy nową instancję |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/pl/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Tworzy nową instancję |

## Metody

| Metoda | Opis |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/pl/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Wywoływany w celu zapisania nagłówka dokumentu html. Wywoływany raz na konwersję prezentacji. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/pl/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Wywoływany w celu zapisania stopki dokumentu html. Wywoływany raz na konwersję prezentacji. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/pl/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Wywoływany w celu zapisania nagłówka slajdu html. Wywoływany raz dla każdego slajdu. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/pl/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Wywoływany w celu zapisania stopki slajdu html. Wywoływany raz dla każdego slajdu. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/pl/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Wywoływany przed renderowaniem kształtu. Wywoływany raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, bieżące generowanie obrazu slajdu zostanie zakończone, dodany fragment html zostanie wstawiony i nowy obraz zostanie rozpoczęty na szczycie poprzedniego. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/pl/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Wywoływany przed renderowaniem kształtu. Wywoływany raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, bieżące generowanie obrazu slajdu zostanie zakończone, dodany fragment html zostanie wstawiony i nowy obraz zostanie rozpoczęty na szczycie poprzedniego. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/pl/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Zapisuje wszystkie czcionki zawarte w [`Presentation`](/slides/python-net/pl/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/pl/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Zapisuje dane w formacie base64 bezpośrednio w dokumencie HTML |

### Zobacz także
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)