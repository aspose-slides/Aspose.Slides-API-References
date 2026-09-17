---
title: PPImage class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/ppimage/
---
## PPImage класс

Представляет изображение в презентации.

Тип PPImage раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/ru/aspose.slides/ppimage/binary_data/) | Возвращает копию данных изображения.<br/>            Только для чтения **int**[]. |
| [`image`](/slides/python-net/ru/aspose.slides/ppimage/image/) | Возвращает копию изображения.<br/>            Только для чтения [`IImage`](/slides/python-net/ru/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/ru/aspose.slides/ppimage/svg_image/) | Возвращает или задает объект ISvgImage [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/ru/aspose.slides/ppimage/content_type/) | Возвращает MIME-тип изображения, закодированный в [`PPImage.binary_data`](/slides/python-net/ru/aspose.slides/ppimage/binary_data).<br/>            Только для чтения **str**. |
| [`width`](/slides/python-net/ru/aspose.slides/ppimage/width/) | Возвращает ширину изображения.<br/>            Только для чтения **int**. |
| [`height`](/slides/python-net/ru/aspose.slides/ppimage/height/) | Возвращает высоту изображения.<br/>            Только для чтения **int**. |
| [`x`](/slides/python-net/ru/aspose.slides/ppimage/x/) | Возвращает смещение по оси X изображения.<br/>            Только для чтения **int**. |
| [`y`](/slides/python-net/ru/aspose.slides/ppimage/y/) | Возвращает смещение по оси Y изображения.<br/>            Только для чтения **int**. |

## Методы

| Method | Description |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/ru/aspose.slides/ppimage/replace_image/#bytes) | Заменяет данные изображения.<br/>            Новые данные изображения. Когда параметр newImageData равен None. |
| [`replace_image(self, new_image)`](/slides/python-net/ru/aspose.slides/ppimage/replace_image/#iimage) | Заменяет данные изображения. Внимание: когда Image является метафайлом, он будет растерен. Используйте ReplaceImage(byte[]) вместо этого<br/>            Новое изображение. Когда параметр newImage равен None. |
| [`replace_image(self, new_image)`](/slides/python-net/ru/aspose.slides/ppimage/replace_image/#ippimage) | Заменяет данные изображения.<br/>            Новый IPPImage. Когда параметр newImage равен None. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)