---
title: TiffOptions
second_title: Aspose.Sildes для .NET, справочник API
description: Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате TIFF.
type: docs
weight: 4570
url: /ru/aspose.slides.export/tiffoptions/
---
## TiffOptions класс

Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате TIFF.

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
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Указывает алгоритм преобразования цветного изображения в чёрно-белое. Этот параметр будет применён только если [`CompressionType`](./compressiontype) установлен в CCITT4 или CCITT3 Чтение/запись [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Значение по умолчанию — Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Указывает тип сжатия. Чтение/запись [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или задаёт шрифт, используемый если исходный шрифт не найден. Чтение/запись String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Указывает горизонтальное разрешение в точках на дюйм. Чтение/запись UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Указывает вертикальное разрешение в точках на дюйм. Чтение/запись UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или задаёт визуальный стиль градиента. Чтение/запись [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Указывает размер генерируемого TIFF-изображения. Значение по умолчанию — 0x0, что означает, что размеры генерируемого изображения будут вычисляться на основе значения размера слайда презентации. Чтение/запись Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортированном документе. Только чтение [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Указывает пиксельный формат генерируемых изображений. Чтение/запись [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для обновлений прогресса сохранения в процентах. См. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Указывает, следует ли включать скрытые слайды в генерируемый документ. По умолчанию `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение/запись Boolean. Значение по умолчанию **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Получает или задаёт режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или задаёт объект, получающий предупреждения и решающий, продолжится ли процесс загрузки или будет прерван. Чтение/запись [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Примеры

В следующем примере показано, как конвертировать PowerPoint в TIFF с размером по умолчанию.

```csharp
[C#]
// Создайте объект Presentation, представляющий файл презентации
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Сохранение презентации в документ TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

В следующем примере показано, как конвертировать PowerPoint в TIFF с пользовательским размером.

```csharp
[C#]
// Создайте объект Presentation, представляющий файл презентации
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Создайте экземпляр класса TiffOptions
    TiffOptions opts = new TiffOptions();
    // Установка типа сжатия
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
    // Единица измерения разрешения  всегда равна “2” (точек на дюйм)
    // Установка разрешения изображения DPI
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Установить размер изображения
    opts.ImageSize = new Size(1728, 1078);
    // Сохранить презентацию в TIFF с указанным размером изображения
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

В следующем примере показано, как конвертировать PowerPoint в TIFF с пользовательским пиксельным форматом изображения.

```csharp
[C#]
// Создайте объект Presentation, представляющий файл презентации
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat содержит следующие значения (как указано в документации):
    Format1bppIndexed; // 1 бит на пиксель, индексировано.
    Format4bppIndexed; // 4 бита на пиксель, индексировано.
    Format8bppIndexed; // 8 бит на пиксель, индексировано.
    Format24bppRgb; // 24 бита на пиксель, RGB.
    Format32bppArgb; // 32 бита на пиксель, ARGB.
    */
    // Сохранить презентацию в TIFF с указанным размером изображения
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### См. также

* класс [SaveOptions](../saveoptions)
* интерфейс [ITiffOptions](../itiffoptions)
* пространство имён [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->