---
title: PPImage class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ppimage/
---
## PPImage klass

Representerar en bild i en presentation.

PPImage-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/sv/aspose.slides/ppimage/binary_data/) | Returnerar en kopia av en bilds data.<br/>            Skrivskyddad **int**[]. |
| [`image`](/slides/python-net/sv/aspose.slides/ppimage/image/) | Returnerar en kopia av en bild.<br/>            Skrivskyddad [`IImage`](/slides/python-net/sv/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/sv/aspose.slides/ppimage/svg_image/) | Returnerar eller sätter ISvgImage-objekt [`ISvgImage`](/slides/python-net/sv/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/sv/aspose.slides/ppimage/content_type/) | Returnerar en MIME-typ för en bild, kodad i [`PPImage.binary_data`](/slides/python-net/sv/aspose.slides/ppimage/binary_data).<br/>            Skrivskyddad **str**. |
| [`width`](/slides/python-net/sv/aspose.slides/ppimage/width/) | Returnerar en bredd för en bild.<br/>            Skrivskyddad **int**. |
| [`height`](/slides/python-net/sv/aspose.slides/ppimage/height/) | Returnerar en höjd för en bild.<br/>            Skrivskyddad **int**. |
| [`x`](/slides/python-net/sv/aspose.slides/ppimage/x/) | Returnerar en X-offset för en bild.<br/>            Skrivskyddad **int**. |
| [`y`](/slides/python-net/sv/aspose.slides/ppimage/y/) | Returnerar en Y-offset för en bild.<br/>            Skrivskyddad **int**. |

## Metoder

| Method | Description |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/sv/aspose.slides/ppimage/replace_image/#bytes) | Ersätter bilddata.<br/>            När parametern newImageData är None. |
| [`replace_image(self, new_image)`](/slides/python-net/sv/aspose.slides/ppimage/replace_image/#iimage) | Ersätter bilddata. Observera: när Image är metafil – den kommer att rasteriseras. Använd ReplaceImage(byte[]) istället<br/>            När parametern newImage är None. |
| [`replace_image(self, new_image)`](/slides/python-net/sv/aspose.slides/ppimage/replace_image/#ippimage) | Ersätter bilddata.<br/>            När parametern newImage är None. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)