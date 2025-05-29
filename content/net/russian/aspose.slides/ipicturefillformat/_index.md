---
title: IPictureFillFormat
second_title: Aspose.Slides для .NET API Reference
description: Представляет собой стиль заполнения изображением.
type: docs
weight: 6450
url: /ru/aspose.slides/ipicturefillformat/
---

## Интерфейс IPictureFillFormat

Представляет собой стиль заполнения изображением.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Свойства

| Название | Описание |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Позволяет получить базовый интерфейс IFillParamSource. Только для чтения [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Возвращает или устанавливает количество процентов от реальной высоты изображения, которое отрезано снизу картинки. Чтение/запись Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Возвращает или устанавливает количество процентов от реальной ширины изображения, которое отрезано слева картинки. Чтение/запись Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Возвращает или устанавливает количество процентов от реальной ширины изображения, которое отрезано справа картинки. Чтение/запись Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Возвращает или устанавливает количество процентов от реальной высоты изображения, которое отрезано сверху картинки. Чтение/запись Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Возвращает или устанавливает dpi, который используется для заполнения изображения. Чтение/запись Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Возвращает изображение. Только для чтения [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Возвращает или устанавливает режим заполнения изображения. Чтение/запись [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Возвращает или устанавливает нижний край прямоугольника заполнения, который определяется как процентное смещение от нижнего края ограничивающей рамки фигуры. Положительный процент указывает на внутренний отступ, в то время как отрицательный процент указывает на внешний отступ. Чтение/запись Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Возвращает или устанавливает левый край прямоугольника заполнения, который определяется как процентное смещение от левого края ограничивающей рамки фигуры. Положительный процент указывает на внутренний отступ, в то время как отрицательный процент указывает на внешний отступ. Чтение/запись Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Возвращает или устанавливает правый край прямоугольника заполнения, который определяется как процентное смещение от правого края ограничивающей рамки фигуры. Положительный процент указывает на внутренний отступ, в то время как отрицательный процент указывает на внешний отступ. Чтение/запись Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Возвращает или устанавливает верхний край прямоугольника заполнения, который определяется как процентное смещение от верхнего края ограничивающей рамки фигуры. Положительный процент указывает на внутренний отступ, в то время как отрицательный процент указывает на внешний отступ. Чтение/запись Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Возвращает или устанавливает, как текстура выровнена внутри фигуры. Эта настройка контролирует начальную точку текстурного узора и то, как он повторяется по всей фигуре. Чтение/запись [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Отражает текстуру плитки вокруг ее горизонтальной, вертикальной или обеих осей. Чтение/запись [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Возвращает или устанавливает горизонтальное смещение текстуры от начала фигуры в пунктах. Положительное значение перемещает текстуру вправо, в то время как отрицательное значение перемещает ее влево. Чтение/запись Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Возвращает или устанавливает вертикальное смещение текстуры от начала фигуры в пунктах. Положительное значение перемещает текстуру вниз, в то время как отрицательное значение перемещает ее вверх. Чтение/запись Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Возвращает или устанавливает горизонтальный масштаб для заполнения текстуры в процентах. Чтение/запись Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Возвращает или устанавливает вертикальный масштаб для заполнения текстуры в процентах. Чтение/запись Single. |

## Методы

| Название | Описание |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Сжимает изображение, уменьшая его размер на основе размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Сжимает изображение, уменьшая его размер на основе размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Удаляет обрезанные области заполнения изображения. |

### См. также

* интерфейс [IFillParamSource](../ifillparamsource)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->