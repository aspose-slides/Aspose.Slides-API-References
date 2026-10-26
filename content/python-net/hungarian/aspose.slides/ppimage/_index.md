---
title: PPImage class
second_title: Aspose.Slides Python számára .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/ppimage/
---
## PPImage osztály

Egy képet képvisel egy prezentációban.

A PPImage típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`binary_data`](/slides/python-net/hu/aspose.slides/ppimage/binary_data/) | Visszaadja a kép adatainak másolatát.<br/>            Csak olvasható **int**[]. |
| [`image`](/slides/python-net/hu/aspose.slides/ppimage/image/) | Visszaadja a kép másolatát.<br/>            Csak olvasható [`IImage`](/slides/python-net/hu/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/hu/aspose.slides/ppimage/svg_image/) | Visszaadja vagy beállítja az ISvgImage objektumot [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/hu/aspose.slides/ppimage/content_type/) | Visszaadja a kép MIME típusát, [`PPImage.binary_data`](/slides/python-net/hu/aspose.slides/ppimage/binary_data)-ben kódolva.<br/>            Csak olvasható **str**. |
| [`width`](/slides/python-net/hu/aspose.slides/ppimage/width/) | Visszaadja a kép szélességét.<br/>            Csak olvasható **int**. |
| [`height`](/slides/python-net/hu/aspose.slides/ppimage/height/) | Visszaadja a kép magasságát.<br/>            Csak olvasható **int**. |
| [`x`](/slides/python-net/hu/aspose.slides/ppimage/x/) | Visszaadja a kép X-eltolását.<br/>            Csak olvasható **int**. |
| [`y`](/slides/python-net/hu/aspose.slides/ppimage/y/) | Visszaadja a kép Y-eltolását.<br/>            Csak olvasható **int**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/hu/aspose.slides/ppimage/replace_image/#bytes) | Lecseréli a kép adatát.<br/>            Az új kép adata. Ha a newImageData paraméter None. |
| [`replace_image(self, new_image)`](/slides/python-net/hu/aspose.slides/ppimage/replace_image/#iimage) | Lecseréli a kép adatát. Figyelem: ha a kép metafájl, rasterizálva lesz. Használja a ReplaceImage(byte[]) metódust helyette<br/>            Az új kép. Ha a newImage paraméter None. |
| [`replace_image(self, new_image)`](/slides/python-net/hu/aspose.slides/ppimage/replace_image/#ippimage) | Lecseréli a kép adatát.<br/>            Az új IPPImage. Ha a newImage paraméter None. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)