---
title: PPImage class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ppimage/
---
## PPImage sınıfı

Bir sunumdaki görüntüyü temsil eder.

The PPImage type exposes the following members:

## Özellikler

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/tr/aspose.slides/ppimage/binary_data/) | Bir görüntünün verisinin kopyasını döndürür.<br/>            Yalnızca okuma **int**[]. |
| [`image`](/slides/python-net/tr/aspose.slides/ppimage/image/) | Bir görüntünün kopyasını döndürür.<br/>            Yalnızca okuma [`IImage`](/slides/python-net/tr/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/tr/aspose.slides/ppimage/svg_image/) | ISvgImage nesnesini [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage) döndürür veya ayarlar |
| [`content_type`](/slides/python-net/tr/aspose.slides/ppimage/content_type/) | Bir görüntünün [`PPImage.binary_data`](/slides/python-net/tr/aspose.slides/ppimage/binary_data) içinde kodlanmış MIME türünü döndürür.<br/>            Yalnızca okuma **str**. |
| [`width`](/slides/python-net/tr/aspose.slides/ppimage/width/) | Bir görüntünün genişliğini döndürür.<br/>            Yalnızca okuma **int**. |
| [`height`](/slides/python-net/tr/aspose.slides/ppimage/height/) | Bir görüntünün yüksekliğini döndürür.<br/>            Yalnızca okuma **int**. |
| [`x`](/slides/python-net/tr/aspose.slides/ppimage/x/) | Bir görüntünün X ofsetini döndürür.<br/>            Yalnızca okuma **int**. |
| [`y`](/slides/python-net/tr/aspose.slides/ppimage/y/) | Bir görüntünün Y ofsetini döndürür.<br/>            Yalnızca okuma **int**. |

## Metotlar

| Method | Description |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/tr/aspose.slides/ppimage/replace_image/#bytes) | Görüntü verisini değiştirir.<br/>            Yeni görüntünün verisi. newImageData parametresi None olduğunda. |
| [`replace_image(self, new_image)`](/slides/python-net/tr/aspose.slides/ppimage/replace_image/#iimage) | Görüntü verisini değiştirir. Dikkat: Image bir metafile ise rasterleştirilecektir. ReplaceImage(byte[]) yerine kullanın<br/>            Yeni görüntü. newImage parametresi None olduğunda. |
| [`replace_image(self, new_image)`](/slides/python-net/tr/aspose.slides/ppimage/replace_image/#ippimage) | Görüntü verisini değiştirir.<br/>            Yeni IPPImage. newImage parametresi None olduğunda. |


### Ayrıca bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)