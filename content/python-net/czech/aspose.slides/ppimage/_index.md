---
title: PPImage class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ppimage/
---
## PPImage třída

Představuje obrázek v prezentaci.

Typ PPImage poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`binary_data`](/slides/python-net/cs/aspose.slides/ppimage/binary_data/) | Vrací kopii dat obrázku.<br/>            Pouze pro čtení **int**[]. |
| [`image`](/slides/python-net/cs/aspose.slides/ppimage/image/) | Vrací kopii obrázku.<br/>            Pouze pro čtení [`IImage`](/slides/python-net/cs/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/cs/aspose.slides/ppimage/svg_image/) | Vrací nebo nastavuje objekt ISvgImage [`ISvgImage`](/slides/python-net/cs/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/cs/aspose.slides/ppimage/content_type/) | Vrací MIME typ obrázku, kódovaný v [`PPImage.binary_data`](/slides/python-net/cs/aspose.slides/ppimage/binary_data).<br/>            Pouze pro čtení **str**. |
| [`width`](/slides/python-net/cs/aspose.slides/ppimage/width/) | Vrací šířku obrázku.<br/>            Pouze pro čtení **int**. |
| [`height`](/slides/python-net/cs/aspose.slides/ppimage/height/) | Vrací výšku obrázku.<br/>            Pouze pro čtení **int**. |
| [`x`](/slides/python-net/cs/aspose.slides/ppimage/x/) | Vrací X-posun obrázku.<br/>            Pouze pro čtení **int**. |
| [`y`](/slides/python-net/cs/aspose.slides/ppimage/y/) | Vrací Y-posun obrázku.<br/>            Pouze pro čtení **int**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/cs/aspose.slides/ppimage/replace_image/#bytes) | Nahrazuje data obrázku.<br/>            Nová data obrázku.Když je parametr newImageData None. |
| [`replace_image(self, new_image)`](/slides/python-net/cs/aspose.slides/ppimage/replace_image/#iimage) | Nahrazuje data obrázku. Pozor: když je Image metafile – bude rasterizována. Použijte ReplaceImage(byte[]) místo<br/>            Nový obrázek.Když je parametr newImage None. |
| [`replace_image(self, new_image)`](/slides/python-net/cs/aspose.slides/ppimage/replace_image/#ippimage) | Nahrazuje data obrázku.<br/>            Nový IPPImage.Když je parametr newImage None. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)