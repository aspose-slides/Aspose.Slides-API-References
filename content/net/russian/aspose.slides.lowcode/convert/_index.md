---
title: Convert
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет группу методов, предназначенных для преобразования Presentation../aspose.slides/presentation.
type: docs
weight: 7880
url: /ru/aspose.slides.lowcode/convert/
---
## Convert класс

Represents a group of methods intended to convert [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Методы

| Имя | Описание |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Преобразует [`Presentation`](../../aspose.slides/presentation) с использованием переданного расширения пути вывода для определения требуемого формата экспорта. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Преобразует входную презентацию в набор изображений формата JPEG. Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Преобразует входную презентацию в набор изображений формата JPEG. Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Преобразует входную презентацию в набор изображений формата JPEG. Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Преобразует [`Presentation`](../../aspose.slides/presentation) в PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Преобразует [`Presentation`](../../aspose.slides/presentation) в PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Преобразует [`Presentation`](../../aspose.slides/presentation) в PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Преобразует [`Presentation`](../../aspose.slides/presentation) в PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Преобразует входную презентацию в набор изображений формата PNG. Если имя выходного файла указано как "myPath/myFilename.png", результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N — номер слайда. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Преобразует входную презентацию в набор изображений формата PNG. Если имя выходного файла указано как "myPath/myFilename.png", результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N — номер слайда. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Преобразует входную презентацию в набор изображений формата PNG. Если имя выходного файла указано как "myPath/myFilename.png", результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N — номер слайда. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Преобразует [`Presentation`](../../aspose.slides/presentation) в SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Преобразует [`Presentation`](../../aspose.slides/presentation) в SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Преобразует [`Presentation`](../../aspose.slides/presentation) в SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Преобразует [`Presentation`](../../aspose.slides/presentation) в SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Преобразует [`Presentation`](../../aspose.slides/presentation) в SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Преобразует входную презентацию в набор изображений формата TIFF. Если имя выходного файла указано как "myPath/myFilename.tiff", результат будет сохранён как набор файлов "myPath/myFilename_N.tiff", где N — номер слайда. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Преобразует входную презентацию в формат TIFF с пользовательскими параметрами. Если имя выходного файла указано как "myPath/myFilename.tiff" и *multipage* равно `false`, результат будет сохранён как набор файлов "myPath/myFilename_N.tiff", где N — номер слайда. В противном случае, если *multipage* равно `true`, результат будет представлять собой многостраничный документ "myPath/myFilename.tiff". |

## Другие члены

| Имя | Описание |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Обратный вызов, который будет вызываться для каждого [`Slide`](../../aspose.slides/slide), ожидается возвращаемый путь вывода. |

### Примеры

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### См. также

* пространство имён [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->