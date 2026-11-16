---
title: IPictureFillFormat
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет стиль заливки изображением.
type: docs
weight: 6670
url: /ru/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat интерфейс

Представляет стиль заливки изображением.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Позволяет получить базовый интерфейс IFillParamSource. Только для чтения [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Возвращает или задает количество процентов реальной высоты изображения, которое обрезано снизу картинки. Чтение/запись Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Возвращает или задает количество процентов реальной ширины изображения, которое обрезано слева от картинки. Чтение/запись Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Возвращает или задает количество процентов реальной ширины изображения, которое обрезано справа от картинки. Чтение/запись Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Возвращает или задает количество процентов реальной высоты изображения, которое обрезано сверху картинки. Чтение/запись Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Возвращает или задает dpi, используемый для заполнения картинки. Чтение/запись Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Возвращает картинку. Только для чтения [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Возвращает или задает режим заполнения картинки. Чтение/запись [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Возвращает или задает нижнюю грань прямоугольника заполнения, определяемую процентным смещением от нижней грани ограничивающего бокса фигуры. Положительный процент указывает на вложение, отрицательный — на выступ. Чтение/запись Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Возвращает или задает левую грань прямоугольника заполнения, определяемую процентным смещением от левой грани ограничивающего бокса фигуры. Положительный процент указывает на вложение, отрицательный — на выступ. Чтение/запись Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Возвращает или задает правую грань прямоугольника заполнения, определяемую процентным смещением от правой грани ограничивающего бокса фигуры. Положительный процент указывает на вложение, отрицательный — на выступ. Чтение/запись Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Возвращает или задает верхнюю грань прямоугольника заполнения, определяемую процентным смещением от верхней грани ограничивающего бокса фигуры. Положительный процент указывает на вложение, отрицательный — на выступ. Чтение/запись Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Возвращает или задает способ выравнивания текстуры внутри фигуры. Этот параметр управляет начальной точкой шаблона текстуры и тем, как он повторяется по фигуре. Чтение/запись [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Отражает плитку текстуры по горизонтальной, вертикальной или обеим осям. Чтение/запись [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Возвращает или задает горизонтальное смещение текстуры от начала координат фигуры в пунктах. Положительное значение сдвигает текстуру вправо, отрицательное — влево. Чтение/запись Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Возвращает или задает вертикальное смещение текстуры от начала координат фигуры в пунктах. Положительное значение сдвигает текстуру вниз, отрицательное — вверх. Чтение/запись Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Возвращает или задает горизонтальный масштаб заполнения текстурой в процентах. Чтение/запись Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Возвращает или задает вертикальный масштаб заполнения текстурой в процентах. Чтение/запись Single. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Сжимает изображение, уменьшая его размер в зависимости от размеров фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Сжимает изображение, уменьшая его размер в зависимости от размеров фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Удаляет обрезанные области заполнения картинки. |

### Смотрите также

* интерфейс [IFillParamSource](../ifillparamsource)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->