---
title: PictureFillFormat
second_title: Aspose.Sildes для .NET API Reference
description: Представляет стиль заполнения изображения.
type: docs
weight: 9120
url: /ru/aspose.slides/picturefillformat/
---

## PictureFillFormat class

Представляет стиль заполнения изображения.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Возвращает или задает количество процентов от реальной высоты изображения, которое обрезается снизу картинки. Чтение/запись Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Возвращает или задает количество процентов от реальной ширины изображения, которое обрезается слева картинки. Чтение/запись Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Возвращает или задает количество процентов от реальной ширины изображения, которое обрезается справа картинки. Чтение/запись Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Возвращает или задает количество процентов от реальной высоты изображения, которое обрезается сверху картинки. Чтение/запись Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Возвращает или задает dpi, который используется для заполнения картинки. Чтение/запись Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Возвращает картинку. Только для чтения [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Возвращает или задает режим заполнения картинки. Чтение/запись [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Возвращает или задает нижний край заполненного прямоугольника, который определяется процентным смещением от нижнего края ограничивающего прямоугольника фигуры. Положительное значение указывает на внутреннее смещение, в то время как отрицательное значение указывает на внешнее смещение. Чтение/запись Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Возвращает или задает левый край заполненного прямоугольника, который определяется процентным смещением от левого края ограничивающего прямоугольника фигуры. Положительное значение указывает на внутреннее смещение, в то время как отрицательное значение указывает на внешнее смещение. Чтение/запись Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Возвращает или задает правый край заполненного прямоугольника, который определяется процентным смещением от правого края ограничивающего прямоугольника фигуры. Положительное значение указывает на внутреннее смещение, в то время как отрицательное значение указывает на внешнее смещение. Чтение/запись Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Возвращает или задает верхний край заполненного прямоугольника, который определяется процентным смещением от верхнего края ограничивающего прямоугольника фигуры. Положительное значение указывает на внутреннее смещение, в то время как отрицательное значение указывает на внешнее смещение. Чтение/запись Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Возвращает или задает, как текстура выравнивается внутри фигуры. Эта настройка управляет начальной точкой текстурного узора и тем, как он повторяется по всей фигуре. Чтение/запись [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Поворачивает текстурную плитку вокруг ее горизонтальной, вертикальной или обеих осей. Чтение/запись [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Возвращает или задает горизонтальное смещение текстуры от начала фигуры в пунктах. Положительное значение перемещает текстуру вправо, в то время как отрицательное значение перемещает ее влево. Чтение/запись Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Возвращает или задает вертикальное смещение текстуры от начала фигуры в пунктах. Положительное значение перемещает текстуру вниз, в то время как отрицательное значение перемещает ее вверх. Чтение/запись Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Возвращает или задает горизонтальный масштаб для заполнения текстуры в процентах. Чтение/запись Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Возвращает или задает вертикальный масштаб для заполнения текстуры в процентах. Чтение/запись Single. |

## Methods

| Name | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Сжимает изображение, уменьшая его размер на основе размера фигуры и заданного разрешения. При желании также удаляет обрезанные области. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Сжимает изображение, уменьшая его размер на основе размера фигуры и заданного разрешения. При желании также удаляет обрезанные области. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Удаляет обрезанные области заполненной картинки. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с заданным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает код хеширования. |

### See Also

* class [PVIObject](../pviobject)
* interface [IPictureFillFormat](../ipicturefillformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->