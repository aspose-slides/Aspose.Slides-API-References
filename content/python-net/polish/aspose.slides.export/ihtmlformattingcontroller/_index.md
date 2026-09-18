---
title: IHtmlFormattingController class
second_title: Aspose.Slides dla Python przez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController klasa

Kontroluje generowanie pliku html.

Typ IHtmlFormattingController udostępnia następujące elementy:

## Metody

| Metoda | Opis |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/pl/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Wywoływana w celu zapisania nagłówka dokumentu html. Wywoływana raz na konwersję prezentacji. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/pl/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Wywoływana w celu zapisania stopki dokumentu html. Wywoływana raz na konwersję prezentacji. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/pl/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Wywoływana w celu zapisania nagłówka slajdu html. Wywoływana raz dla każdego slajdu. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/pl/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Wywoływana w celu zapisania stopki slajdu html. Wywoływana raz dla każdego slajdu. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/pl/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, bieżące generowanie obrazu slajdu zostanie zakończone, dodany fragment html zostanie wstawiony i nowy obraz zostanie rozpoczęty nad poprzednim. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/pl/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, bieżące generowanie obrazu slajdu zostanie zakończone, dodany fragment html zostanie wstawiony i nowy obraz zostanie rozpoczęty nad poprzednim. |

### Zobacz także
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)