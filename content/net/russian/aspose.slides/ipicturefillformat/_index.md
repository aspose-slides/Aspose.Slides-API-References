---
title: IPictureFillFormat
second_title: Aspose.Sildes для .NET справки API
description: Представляет стиль заливки картинкой.
type: docs
weight: 6650
url: /ru/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat интерфейс

Представляет стиль заливки картинкой.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Свойства

| Name | Description |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Позволяет получить базовый интерфейс IFillParamSource. Только чтение [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Возвращает или задает количество процентов реальной высоты изображения, обрезаемой снизу картинки. Чтение/запись Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Возвращает или задает количество процентов реальной ширины изображения, обрезаемой слева картинки. Чтение/запись Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Возвращает или задает количество процентов реальной ширины изображения, обрезаемой справа картинки. Чтение/запись Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Возвращает или задает количество процентов реальной высоты изображения, обрезаемой сверху картинки. Чтение/запись Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Возвращает или задает DPI, используемый для заполнения изображения. Чтение/запись Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Возвращает изображение. Только чтение [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Возвращает или задает режим заливки изображения. Чтение/запись [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Возвращает или задает нижний край прямоугольника заливки, определяемый процентным смещением от нижнего края ограничивающего прямоугольника фигуры. Положительный процент указывает на вложение, отрицательный — на выступ. Чтение/запись Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Возвращает или задает левый край прямоугольника заливки, определяемый процентным смещением от левого края ограничивающего прямоугольника фигуры. Положительный процент указывает на вложение, отрицательный — на выступ. Чтение/запись Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Возвращает или задает правый край прямоугольника заливки, определяемый процентным смещением от правого края ограничивающего прямоугольника фигуры. Положительный процент указывает на вложение, отрицательный — на выступ. Чтение/запись Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Возвращает или задает верхний край прямоугольника заливки, определяемый процентным смещением от верхнего края ограничивающего прямоугольника фигуры. Положительный процент указывает на вложение, отрицательный — на выступ. Чтение/запись Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Возвращает или задает выравнивание текстуры внутри фигуры. Эта настройка управляет начальной точкой узора текстуры и тем, как он повторяется по фигуре. Чтение/запись [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Отражает фрагмент текстуры по горизонтальной, вертикальной или обеим осям. Чтение/запись [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Возвращает или задает горизонтальное смещение текстуры от начала координат фигуры в пунктах. Положительное значение перемещает текстуру вправо, отрицательное — влево. Чтение/запись Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Возвращает или задает вертикальное смещение текстуры от начала координат фигуры в пунктах. Положительное значение перемещает текстуру вниз, отрицательное — вверх. Чтение/запись Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Возвращает или задает горизонтальный масштаб заливки текстурой в процентах. Чтение/запись Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Возвращает или задает вертикальный масштаб заливки текстурой в процентах. Чтение/запись Single. |

## Методы

| Name | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Сжимает изображение, уменьшая его размер на основе размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Сжимает изображение, уменьшая его размер на основе размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Удаляет обрезанные области заливки изображения. |

### См. также

* интерфейс [IFillParamSource](../ifillparamsource)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->