---
title: PictureFillFormat
second_title: Aspose.Sildes для .NET справочник API
description: Представляет стиль заливки картинкой.
type: docs
weight: 9410
url: /ru/aspose.slides/picturefillformat/
---
## PictureFillFormat класс

Представляет стиль заливки картинкой.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Свойства

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Возвращает или задаёт количество процентов реальной высоты изображения, которое обрезается снизу картинки. Чтение/запись Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Возвращает или задаёт количество процентов реальной ширины изображения, которое обрезается слева картинки. Чтение/запись Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Возвращает или задаёт количество процентов реальной ширины изображения, которое обрезается справа картинки. Чтение/запись Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Возвращает или задаёт количество процентов реальной высоты изображения, которое обрезается сверху картинки. Чтение/запись Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Возвращает или задаёт dpi, используемый для заливки картинкой. Чтение/запись Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Возвращает картинку. Только для чтения [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Возвращает или задаёт режим заливки картинкой. Чтение/запись [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Возвращает или задаёт нижний край прямоугольника заливки, определённый смещением в процентах от нижнего края ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Чтение/запись Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Возвращает или задаёт левый край прямоугольника заливки, определённый смещением в процентах от левого края ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Чтение/запись Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Возвращает или задаёт правый край прямоугольника заливки, определённый смещением в процентах от правого края ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Чтение/запись Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Возвращает или задаёт верхний край прямоугольника заливки, определённый смещением в процентах от верхнего края ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Чтение/запись Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Возвращает или задаёт способ выравнивания текстуры внутри фигуры. Эта настройка определяет начальную точку узора текстуры и то, как он повторяется по фигуре. Чтение/запись [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Переворачивает плитку текстуры по её горизонтальной, вертикальной или обеим осям. Чтение/запись [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Возвращает или задаёт горизонтальное смещение текстуры от начала фигуры в пунктах. Положительное значение смещает текстуру вправо, отрицательное — влево. Чтение/запись Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Возвращает или задаёт вертикальное смещение текстуры от начала фигуры в пунктах. Положительное значение смещает текстуру вниз, отрицательное — вверх. Чтение/запись Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Возвращает или задаёт горизонтальный масштаб заливки текстурой в процентах. Чтение/запись Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Возвращает или задаёт вертикальный масштаб заливки текстурой в процентах. Чтение/запись Single. |

## Методы

| Name | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Сжимает изображение, уменьшая его размер на основе размеров фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Сжимает изображение, уменьшая его размер на основе размеров фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Удаляет обрезанные области заливочного изображения. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает код хэша. |

### См. также

* класс [PVIObject](../pviobject)
* интерфейс [IPictureFillFormat](../ipicturefillformat)
* пространство имён [Aspose.Slides](../../aspose.slides)
* ассемблея [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->