---
title: ISVGOptions
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет параметры SVG.
type: docs
weight: 3730
url: /ru/aspose.slides.export/isvgoptions/
---
## ISVGOptions interface

Представляет параметры SVG.

```csharp
public interface ISVGOptions : ISaveOptions
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export/isvgoptions/asisaveoptions) { get; } | Возвращает интерфейс ISaveOptions. Только для чтения[`ISaveOptions`](../isaveoptions). |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/isvgoptions/deletepicturescroppedareas) { get; set; } | Логический флаг указывает, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены, если false, они будут сериализованы в документе (что может привести к увеличению файла ) Read/ записьBoolean. |
| [Disable3DText](../../aspose.slides.export/isvgoptions/disable3dtext) { get; set; } | Определяет, отключен ли 3D-текст в SVG. Чтение/записьBoolean. |
| [DisableGradientSplit](../../aspose.slides.export/isvgoptions/disablegradientsplit) { get; set; } | Отключает разделение градиентов FromCornerX и FromCenter. Чтение/записьBoolean. |
| [DisableLineEndCropping](../../aspose.slides.export/isvgoptions/disablelineendcropping) { get; set; } | В SVG 1.1 отсутствует возможность определять вставки для маркеров. Механизм записи SVG Aspose.Slides имеет обходной путь для этой проблемы: он обрезает конец строки стрелкой, поэтому линия не перекрывает маркеры. Эта опция отключает такое поведение. Чтение/записьBoolean. |
| [ExternalFontsHandling](../../aspose.slides.export/isvgoptions/externalfontshandling) { get; set; } | Определяет способ обработки загруженных извне шрифтов. Чтение/запись[`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [JpegQuality](../../aspose.slides.export/isvgoptions/jpegquality) { get; set; } | Определяет качество кодирования JPEG. Чтение/записьInt32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/isvgoptions/metafilerasterizationdpi) { get; set; } | Возвращает или задает нижний предел разрешения для растеризации метафайла. Чтение/записьInt32. |
| [PicturesCompression](../../aspose.slides.export/isvgoptions/picturescompression) { get; set; } | Представляет уровень сжатия изображений Чтение/запись[`PicturesCompression`](./picturescompression). |
| [ShapeFormattingController](../../aspose.slides.export/isvgoptions/shapeformattingcontroller) { get; set; } | Возвращает и устанавливает интерфейс обратного вызова, который позволяет пользователю управлять преобразованием формы. Чтение/запись[`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [VectorizeText](../../aspose.slides.export/isvgoptions/vectorizetext) { get; set; } | Определяет, будет ли текст на слайде сохранен как графика. Чтение/записьBoolean. |

### Смотрите также

* interface [ISaveOptions](../isaveoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
