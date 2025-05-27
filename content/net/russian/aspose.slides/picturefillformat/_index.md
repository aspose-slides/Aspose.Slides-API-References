---
title: PictureFillFormat
second_title: Справочник API Aspose.Slides для .NET
description: Представляет стиль заливки изображением.
type: docs
weight: 9120
url: /ru/aspose.slides/picturefillformat/
---

## Класс PictureFillFormat

Представляет стиль заливки изображением.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Свойства

| Название | Описание |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Возвращает или задает количество процентов от реальной высоты изображения, которое обрезается снизу картинки. Чтение/запись Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Возвращает или задает количество процентов от реальной ширины изображения, которое обрезается слева картинки. Чтение/запись Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Возвращает или задает количество процентов от реальной ширины изображения, которое обрезается справа картинки. Чтение/запись Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Возвращает или задает количество процентов от реальной высоты изображения, которое обрезается сверху картинки. Чтение/запись Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Возвращает или задает разрешение, которое используется для заливки изображения. Чтение/запись Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Возвращает изображение. Только для чтения [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Возвращает или задает режим заливки картинки. Чтение/запись [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Возвращает или задает нижний край прямоугольника заливки, который определяется процентным смещением от нижнего края ограничивающего прямоугольника формы. Положительный процент указывает на внутреннее смещение, в то время как отрицательный процент указывает на внешнее смещение. Чтение/запись Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Возвращает или задает левый край прямоугольника заливки, который определяется процентным смещением от левого края ограничивающего прямоугольника формы. Положительный процент указывает на внутреннее смещение, в то время как отрицательный процент указывает на внешнее смещение. Чтение/запись Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Возвращает или задает правый край прямоугольника заливки, который определяется процентным смещением от правого края ограничивающего прямоугольника формы. Положительный процент указывает на внутреннее смещение, в то время как отрицательный процент указывает на внешнее смещение. Чтение/запись Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Возвращает или задает верхний край прямоугольника заливки, который определяется процентным смещением от верхнего края ограничивающего прямоугольника формы. Положительный процент указывает на внутреннее смещение, в то время как отрицательный процент указывает на внешнее смещение. Чтение/запись Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Возвращает или задает, как текстура выравнивается внутри формы. Эта настройка контролирует начало текстурного шаблона и его повторение по всей форме. Чтение/запись [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Отражает текстурную плитку вокруг своей горизонтальной, вертикальной или обеих осей. Чтение/запись [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Возвращает или задает горизонтальное смещение текстуры от начала формы в пунктах. Положительное значение сдвигает текстуру вправо, в то время как отрицательное значение сдвигает её влево. Чтение/запись Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Возвращает или задает вертикальное смещение текстуры от начала формы в пунктах. Положительное значение сдвигает текстуру вниз, в то время как отрицательное значение сдвигает её вверх. Чтение/запись Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Возвращает или задает горизонтальный масштаб для заливки текстуры в процентах. Чтение/запись Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Возвращает или задает вертикальный масштаб для заливки текстуры в процентах. Чтение/запись Single. |

## Методы

| Название | Описание |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Сжимает изображение, уменьшая его размер на основе размера формы и заданного разрешения. При желании также удаляет обрезанные области. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Сжимает изображение, уменьшая его размер на основе размера формы и заданного разрешения. При желании также удаляет обрезанные области. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Удаляет обрезанные области заливки изображения. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хэш-код. |

### Смотрите также

* класс [PVIObject](../pviobject)
* интерфейс [IPictureFillFormat](../ipicturefillformat)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->