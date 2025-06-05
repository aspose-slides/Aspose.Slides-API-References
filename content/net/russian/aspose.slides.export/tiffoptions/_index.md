---
title: TiffOptions
second_title: Aspose.Sildes для .NET API Справочник
description: Предоставляет параметры, которые контролируют, как презентация сохраняется в формате TIFF.
type: docs
weight: 4380
url: /ru/aspose.slides.export/tiffoptions/
---

## Класс TiffOptions

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TiffOptions](tiffoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Определяет алгоритм для преобразования цветного изображения в черно-белое. Этот параметр будет применен только в том случае, если [`CompressionType`](./compressiontype) установлен на CCITT4 или CCITT3 Чтение/запись [`BlackWhiteConversionMode`](../blackwhiteconversionmode). По умолчанию значение – Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Указывает тип сжатия. Чтение/запись [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Чтение/запись строка. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Указывает горизонтальное разрешение в точках на дюйм. Чтение/запись UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Указывает вертикальное разрешение в точках на дюйм. Чтение/запись UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или устанавливает визуальный стиль градиента. Чтение/запись [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Указывает размер сгенерированного TIFF-изображения. Значение по умолчанию 0x0, что означает, что размеры сгенерированного изображения будут рассчитываться на основе значения размера слайда презентации. Чтение/запись размер. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортированном документе. Только для чтения [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Указывает цветовой формат для сгенерированных изображений. Чтение/запись [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для обновлений по ходу сохранения в процентах. Смотрите [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Указывает, должен ли сгенерированный документ включать скрытые слайды или нет. По умолчанию значение `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение/запись Boolean. Значение по умолчанию **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Получает или устанавливает режим, в котором слайды размещаются на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или устанавливает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. Чтение/запись [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Примеры

Следующий пример показывает, как конвертировать PowerPoint в TIFF с размером по умолчанию.

```csharp
[C#]
// Создаем объект Presentation, представляющий файл презентации
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Сохраняем презентацию в документ TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Следующий пример показывает, как конвертировать PowerPoint в TIFF с пользовательским размером.

```csharp
[C#]
// Создаем объект Presentation, представляющий файл презентации
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Создаем класс TiffOptions
    TiffOptions opts = new TiffOptions();
    // Устанавливаем тип сжатия
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Типы сжатия
    // Default - Указывает схему сжатия по умолчанию (LZW).
    // None - Указывает отсутствие сжатия.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Глубина зависит от типа сжатия и не может быть установлена вручную.
    // Единица разрешения всегда равна "2" (точек на дюйм)
    // Устанавливаем DPI изображения
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Устанавливаем размер изображения
    opts.ImageSize = new Size(1728, 1078);
    // Сохраняем презентацию в TIFF с указанным размером изображения
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Следующий пример показывает, как конвертировать PowerPoint в TIFF с пользовательским цветовым форматом изображения.

```csharp
[C#]
// Создаем объект Presentation, представляющий файл презентации
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat содержит следующие значения (как можно увидеть из документации):
    Format1bppIndexed; // 1 бит на пиксель, индексированный.
    Format4bppIndexed; // 4 бита на пиксель, индексированный.
    Format8bppIndexed; // 8 бит на пиксель, индексированный.
    Format24bppRgb; // 24 бита на пиксель, RGB.
    Format32bppArgb; // 32 бита на пиксель, ARGB.
    */
    // Сохраняем презентацию в TIFF с указанным форматом пикселей изображения
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Смотрите также

* класс [SaveOptions](../saveoptions)
* интерфейс [ITiffOptions](../itiffoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->