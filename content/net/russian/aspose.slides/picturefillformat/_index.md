---
title: PictureFillFormat
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет стиль заполнения изображением.
type: docs
weight: 9390
url: /ru/aspose.slides/picturefillformat/
---
## PictureFillFormat класс

Представляет стиль заполнения изображением.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Возвращает или задаёт количество процентов реальной высоты изображения, которое обрезается снизу картинки. Чтение/запись Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Возвращает или задаёт количество процентов реальной ширины изображения, которое обрезается слева картинки. Чтение/запись Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Возвращает или задаёт количество процентов реальной ширины изображения, которое обрезается справа картинки. Чтение/запись Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Возвращает или задаёт количество процентов реальной высоты изображения, которое обрезается сверху картинки. Чтение/запись Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Возвращает или задаёт dpi, который используется для заполнения изображения. Чтение/запись Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Возвращает изображение. Только для чтения [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Возвращает или задаёт режим заполнения изображения. Чтение/запись [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Возвращает или задаёт нижний край прямоугольника заливки, определяемый процентным смещением от нижнего края ограничивающего прямоугольника фигуры. Положительный процент указывает отступ, отрицательный — выступ. Чтение/запись Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Возвращает или задаёт левый край прямоугольника заливки, определяемый процентным смещением от левого края ограничивающего прямоугольника фигуры. Положительный процент указывает отступ, отрицательный — выступ. Чтение/запись Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Возвращает или задаёт правый край прямоугольника заливки, определяемый процентным смещением от правого края ограничивающего прямоугольника фигуры. Положительный процент указывает отступ, отрицательный — выступ. Чтение/запись Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Возвращает или задаёт верхний край прямоугольника заливки, определяемый процентным смещением от верхнего края ограничивающего прямоугольника фигуры. Положительный процент указывает отступ, отрицательный — выступ. Чтение/запись Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Возвращает или задаёт выравнивание текстуры внутри фигуры. Эта настройка определяет начальную точку шаблона текстуры и то, как она повторяется по фигуре. Чтение/запись [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Отражает плитку текстуры по её горизонтальной, вертикальной или обеим осям. Чтение/запись [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Возвращает или задаёт горизонтальное смещение текстуры от начала координат фигуры в пунктах. Положительное значение смещает текстуру вправо, отрицательное — влево. Чтение/запись Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Возвращает или задаёт вертикальное смещение текстуры от начала координат фигуры в пунктах. Положительное значение смещает текстуру вниз, отрицательное — вверх. Чтение/запись Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Возвращает или задаёт горизонтальный масштаб заполнения текстурой в процентах. Чтение/запись Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Возвращает или задаёт вертикальный масштаб заполнения текстурой в процентах. Чтение/запись Single. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Сжимает изображение, уменьшая его размер в зависимости от размеров фигуры и указанного разрешения. При желании также удаляет обрезанные области. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Сжимает изображение, уменьшая его размер в зависимости от размеров фигуры и указанного разрешения. При желании также удаляет обрезанные области. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Удаляет обрезанные области заполнения изображения. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хеш-код. |

### См. также

* класс [PVIObject](../pviobject)
* интерфейс [IPictureFillFormat](../ipicturefillformat)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->