---
title: PPImage class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ppimage/
---
## PPImage Klasse

Stellt ein Bild in einer Präsentation dar.

Der PPImage-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/de/aspose.slides/ppimage/binary_data/) | Gibt eine Kopie der Bilddaten zurück.<br/>            Nur lesbar **int**[]. |
| [`image`](/slides/python-net/de/aspose.slides/ppimage/image/) | Gibt eine Kopie des Bildes zurück.<br/>            Nur lesbar [`IImage`](/slides/python-net/de/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/de/aspose.slides/ppimage/svg_image/) | Gibt das ISvgImage-Objekt zurück oder setzt es [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/de/aspose.slides/ppimage/content_type/) | Gibt einen MIME-Typ eines Bildes zurück, kodiert in [`PPImage.binary_data`](/slides/python-net/de/aspose.slides/ppimage/binary_data).<br/>            Nur lesbar **str**. |
| [`width`](/slides/python-net/de/aspose.slides/ppimage/width/) | Gibt die Breite eines Bildes zurück.<br/>            Nur lesbar **int**. |
| [`height`](/slides/python-net/de/aspose.slides/ppimage/height/) | Gibt die Höhe eines Bildes zurück.<br/>            Nur lesbar **int**. |
| [`x`](/slides/python-net/de/aspose.slides/ppimage/x/) | Gibt den X-Offset eines Bildes zurück.<br/>            Nur lesbar **int**. |
| [`y`](/slides/python-net/de/aspose.slides/ppimage/y/) | Gibt den Y-Offset eines Bildes zurück.<br/>            Nur lesbar **int**. |

## Methoden

| Method | Description |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/de/aspose.slides/ppimage/replace_image/#bytes) | Ersetzt Bilddaten.<br/>            Die neuen Bilddaten. Wenn der Parameter newImageData None ist. |
| [`replace_image(self, new_image)`](/slides/python-net/de/aspose.slides/ppimage/replace_image/#iimage) | Ersetzt Bilddaten. Hinweis: Wenn das Bild eine Metadatei ist, wird es rasterisiert. Verwenden Sie stattdessen ReplaceImage(byte[]).<br/>            Das neue Bild. Wenn der Parameter newImage None ist. |
| [`replace_image(self, new_image)`](/slides/python-net/de/aspose.slides/ppimage/replace_image/#ippimage) | Ersetzt Bilddaten.<br/>            Das neue IPPImage. Wenn der Parameter newImage None ist. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)