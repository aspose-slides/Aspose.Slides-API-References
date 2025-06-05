---
title: IPictureFillFormat
second_title: Aspose.Sildes для справки по API .NET
description: Представляет стиль заливки изображением.
type: docs
weight: 6450
url: /ru/aspose.slides/ipicturefillformat/
---

## Интерфейс IPictureFillFormat

Представляет стиль заливки изображением.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Позволяет получить базовый интерфейс IFillParamSource. Только для чтения [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Возвращает или устанавливает число процентов от реальной высоты изображения, которое обрезано снизу. Чтение/запись Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Возвращает или устанавливает число процентов от реальной ширины изображения, которое обрезано слева. Чтение/запись Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Возвращает или устанавливает число процентов от реальной ширины изображения, которое обрезано справа. Чтение/запись Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Возвращает или устанавливает число процентов от реальной высоты изображения, которое обрезано сверху. Чтение/запись Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Возвращает или устанавливает dpi, который используется для заполнения изображения. Чтение/запись Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Возвращает изображение. Только для чтения [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Возвращает или устанавливает режим заливки изображения. Чтение/запись [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Возвращает или устанавливает нижний край заполненного прямоугольника, который определяется процентным смещением от нижнего края границы формы. Положительный процент указывает на вложение, в то время как отрицательный процент указывает на выемку. Чтение/запись Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Возвращает или устанавливает левый край заполненного прямоугольника, который определяется процентным смещением от левого края границы формы. Положительный процент указывает на вложение, в то время как отрицательный процент указывает на выемку. Чтение/запись Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Возвращает или устанавливает правый край заполненного прямоугольника, который определяется процентным смещением от правого края границы формы. Положительный процент указывает на вложение, в то время как отрицательный процент указывает на выемку. Чтение/запись Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Возвращает или устанавливает верхний край заполненного прямоугольника, который определяется процентным смещением от верхнего края границы формы. Положительный процент указывает на вложение, в то время как отрицательный процент указывает на выемку. Чтение/запись Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Возвращает или устанавливает, как текстура выравнивается в форме. Эта настройка контролирует начальную точку текстурного узора и то, как он повторяется по форме. Чтение/запись [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Отражает текстурную плитку вокруг своей горизонтальной, вертикальной или обеих осей. Чтение/запись [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Возвращает или устанавливает горизонтальное смещение текстуры от начала формы в пунктах. Положительное значение перемещает текстуру вправо, в то время как отрицательное значение перемещает её влево. Чтение/запись Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Возвращает или устанавливает вертикальное смещение текстуры от начала формы в пунктах. Положительное значение перемещает текстуру вниз, в то время как отрицательное значение перемещает её вверх. Чтение/запись Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Возвращает или устанавливает горизонтальный масштаб для заливки текстурой в процентах. Чтение/запись Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Возвращает или устанавливает вертикальный масштаб для заливки текстурой в процентах. Чтение/запись Single. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Сжимает изображение, уменьшая его размер на основе размера формы и заданного разрешения. По желанию также удаляет обрезанные области. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Сжимает изображение, уменьшая его размер на основе размера формы и заданного разрешения. По желанию также удаляет обрезанные области. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Удаляет обрезанные области заливки изображения. |

### Также см.


* интерфейс [IFillParamSource](../ifillparamsource)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->