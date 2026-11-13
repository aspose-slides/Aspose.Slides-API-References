---
title: TiffOptions
second_title: Aspose.Sildes для .NET справочник API
description: Предоставляет параметры, контролирующие, как презентация сохраняется в формате TIFF.
type: docs
weight: 4590
url: /ru/aspose.slides.export/tiffoptions/
---
## TiffOptions класс

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
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Указывает алгоритм преобразования цветного изображения в черно-белое. Эта опция применяется только если [`CompressionType`](./compressiontype) установлена в CCITT4 или CCITT3. Чтение/запись [`BlackWhiteConversionMode`](../blackwhiteconversionmode). По умолчанию: Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Указывает тип сжатия. Чтение/запись [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или задает шрифт, используемый если исходный шрифт не найден. Чтение/запись String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Указывает горизонтальное разрешение в точках на дюйм. Чтение/запись UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Указывает вертикальное разрешение в точках на дюйм. Чтение/запись UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или задает визуальный стиль градиента. Чтение/запись [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Указывает размер сгенерированного TIFF-изображения. Значение по умолчанию — 0x0, что означает, что размеры изображения будут рассчитываться на основе размера слайдов презентации. Чтение/запись Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортируемом документе. Только чтение [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Указывает формат пикселей для сгенерированных изображений. Чтение/запись [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. См. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Указывает, должен ли сгенерированный документ включать скрытые слайды. По умолчанию `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение/запись Boolean. Значение по умолчанию — **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Получает или задает режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или отменён. Чтение/запись [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Примеры

В следующем примере показано, как преобразовать PowerPoint в TIFF с размером по умолчанию.

```csharp
[C#]
// Создайте объект Presentation, который представляет файл презентации
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Сохранение презентации в документ TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

В следующем примере показано, как преобразовать PowerPoint в TIFF с пользовательским размером.

```csharp
[C#]
// Создайте объект Presentation, который представляет файл презентации
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Создайте объект класса TiffOptions
    TiffOptions opts = new TiffOptions();
    // Установка типа сжатия
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Типы сжатия
    // Default - указывает схему сжатия по умолчанию (LZW).
    // None - указывает отсутствие сжатия.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Глубина зависит от типа сжатия и не может быть установлена вручную.
    // Единица разрешения всегда равна “2” (точек на дюйм)
    // Установка DPI изображения
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Установить размер изображения
    opts.ImageSize = new Size(1728, 1078);
    // Сохранить презентацию в TIFF с указанным размером изображения
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

В следующем примере показано, как преобразовать PowerPoint в TIFF с пользовательским форматом пикселей изображения.

```csharp
[C#]
// Создайте объект Presentation, который представляет файл презентации
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat содержит следующие значения (как указано в документации):
    Format1bppIndexed; // 1 бит на пиксель, индексированный.
    Format4bppIndexed; // 4 бита на пиксель, индексированный.
    Format8bppIndexed; // 8 бит на пиксель, индексированный.
    Format24bppRgb; // 24 бита на пиксель, RGB.
    Format32bppArgb; // 32 бита на пиксель, ARGB.
    */
    // Сохраните презентацию в TIFF с указанным размером изображения
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### См. также

* класс [SaveOptions](../saveoptions)
* интерфейс [ITiffOptions](../itiffoptions)
* пространство имён [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->