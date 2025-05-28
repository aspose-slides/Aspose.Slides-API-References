---
title: ITiffOptions
second_title: Aspose.Slides для .NET API Reference
description: Предоставляет параметры, которые контролируют, как презентация сохраняется в формате TIFF.
type: docs
weight: 4000
url: /ru/aspose.slides.export/itiffoptions/
---

## Интерфейс ITiffOptions

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате TIFF.

```csharp
public interface ITiffOptions : ISaveOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export/itiffoptions/asisaveoptions) { get; } | Возвращает интерфейс ISaveOptions. Только для чтения [`ISaveOptions`](../isaveoptions). |
| [BwConversionMode](../../aspose.slides.export/itiffoptions/bwconversionmode) { get; set; } | Определяет алгоритм преобразования цветного изображения в черно-белое. Этот параметр будет применен только если [`CompressionType`](./compressiontype) установлен на CCITT4 или CCITT3 Чтение/запись [`BlackWhiteConversionMode`](../blackwhiteconversionmode). По умолчанию - Default. |
| [CompressionType](../../aspose.slides.export/itiffoptions/compressiontype) { get; set; } | Определяет тип сжатия. Чтение/запись [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DpiX](../../aspose.slides.export/itiffoptions/dpix) { get; set; } | Определяет горизонтальное разрешение в точках на дюйм. Чтение/запись UInt32. |
| [DpiY](../../aspose.slides.export/itiffoptions/dpiy) { get; set; } | Определяет вертикальное разрешение в точках на дюйм. Чтение/запись UInt32. |
| [ImageSize](../../aspose.slides.export/itiffoptions/imagesize) { get; set; } | Определяет размер сгенерированного TIFF изображения. Значение по умолчанию - 0x0, что означает, что размеры сгенерированного изображения будут рассчитаны на основе значения размера слайда презентации. Чтение/запись Size. |
| [InkOptions](../../aspose.slides.export/itiffoptions/inkoptions) { get; } | Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортированном документе. Только для чтения [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/itiffoptions/pixelformat) { get; set; } | Определяет пиксельный формат для сгенерированных изображений. Чтение/запись [`ImagePixelFormat`](../imagepixelformat). |
| [ShowHiddenSlides](../../aspose.slides.export/itiffoptions/showhiddenslides) { get; set; } | Определяет, должен ли сгенерированный документ включать скрытые слайды или нет. По умолчанию `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/itiffoptions/slideslayoutoptions) { get; set; } | Получает или устанавливает режим, в котором слайды размещаются на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). |

### Смотрите также

* интерфейс [ISaveOptions](../isaveoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->