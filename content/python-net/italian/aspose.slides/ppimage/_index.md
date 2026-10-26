---
title: PPImage class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ppimage/
---
## classe PPImage

Rappresenta un'immagine in una presentazione.

Il tipo PPImage espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`binary_data`](/slides/python-net/it/aspose.slides/ppimage/binary_data/) | Restituisce una copia dei dati dell'immagine.<br/>            Solo lettura **int**[]. |
| [`image`](/slides/python-net/it/aspose.slides/ppimage/image/) | Restituisce una copia dell'immagine.<br/>            Solo lettura [`IImage`](/slides/python-net/it/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/it/aspose.slides/ppimage/svg_image/) | Restituisce o imposta l'oggetto ISvgImage [`ISvgImage`](/slides/python-net/it/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/it/aspose.slides/ppimage/content_type/) | Restituisce un tipo MIME di un'immagine, codificato in [`PPImage.binary_data`](/slides/python-net/it/aspose.slides/ppimage/binary_data).<br/>            Solo lettura **str**. |
| [`width`](/slides/python-net/it/aspose.slides/ppimage/width/) | Restituisce la larghezza di un'immagine.<br/>            Solo lettura **int**. |
| [`height`](/slides/python-net/it/aspose.slides/ppimage/height/) | Restituisce l'altezza di un'immagine.<br/>            Solo lettura **int**. |
| [`x`](/slides/python-net/it/aspose.slides/ppimage/x/) | Restituisce l'offset X di un'immagine.<br/>            Solo lettura **int**. |
| [`y`](/slides/python-net/it/aspose.slides/ppimage/y/) | Restituisce l'offset Y di un'immagine.<br/>            Solo lettura **int**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/it/aspose.slides/ppimage/replace_image/#bytes) | Sostituisce i dati dell'immagine.<br/>            I nuovi dati dell'immagine.Quando il parametro newImageData è None. |
| [`replace_image(self, new_image)`](/slides/python-net/it/aspose.slides/ppimage/replace_image/#iimage) | Sostituisce i dati dell'immagine. Attenzione: quando l'Image è metafile - verrà rasterizzata. Usa ReplaceImage(byte[]) al suo posto<br/>            La nuova immagine.Quando il parametro newImage è None. |
| [`replace_image(self, new_image)`](/slides/python-net/it/aspose.slides/ppimage/replace_image/#ippimage) | Sostituisce i dati dell'immagine.<br/>            Il nuovo IPPImage.Quando il parametro newImage è None. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)