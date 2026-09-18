---
title: PPImage class
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/ppimage/
---
## PPImage klasa

Reprezentuje obraz w prezentacji.

Typ PPImage udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`binary_data`](/slides/python-net/pl/aspose.slides/ppimage/binary_data/) | Zwraca kopię danych obrazu.<br/>            Tylko do odczytu **int**[]. |
| [`image`](/slides/python-net/pl/aspose.slides/ppimage/image/) | Zwraca kopię obrazu.<br/>            Tylko do odczytu [`IImage`](/slides/python-net/pl/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/pl/aspose.slides/ppimage/svg_image/) | Zwraca lub ustawia obiekt ISvgImage [`ISvgImage`](/slides/python-net/pl/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/pl/aspose.slides/ppimage/content_type/) | Zwraca typ MIME obrazu, zakodowany w [`PPImage.binary_data`](/slides/python-net/pl/aspose.slides/ppimage/binary_data).<br/>            Tylko do odczytu **str**. |
| [`width`](/slides/python-net/pl/aspose.slides/ppimage/width/) | Zwraca szerokość obrazu.<br/>            Tylko do odczytu **int**. |
| [`height`](/slides/python-net/pl/aspose.slides/ppimage/height/) | Zwraca wysokość obrazu.<br/>            Tylko do odczytu **int**. |
| [`x`](/slides/python-net/pl/aspose.slides/ppimage/x/) | Zwraca przesunięcie X obrazu.<br/>            Tylko do odczytu **int**. |
| [`y`](/slides/python-net/pl/aspose.slides/ppimage/y/) | Zwraca przesunięcie Y obrazu.<br/>            Tylko do odczytu **int**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/pl/aspose.slides/ppimage/replace_image/#bytes) | Zastępuje dane obrazu.<br/>            Nowe dane obrazu. Gdy parametr newImageData jest None. |
| [`replace_image(self, new_image)`](/slides/python-net/pl/aspose.slides/ppimage/replace_image/#iimage) | Zastępuje dane obrazu. Uwaga: gdy Image jest metafilem – zostanie zrastrowany. Użyj ReplaceImage(byte[]) zamiast<br/>            Nowy obraz. Gdy parametr newImage jest None. |
| [`replace_image(self, new_image)`](/slides/python-net/pl/aspose.slides/ppimage/replace_image/#ippimage) | Zastępuje dane obrazu.<br/>            Nowy IPPImage. Gdy parametr newImage jest None. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)