---
title: IPdfOptions
second_title: Aspose.Slides для .NET API Reference
description: Предоставляет опции, которые контролируют, как презентация сохраняется в формате Pdf.
type: docs
weight: 3830
url: /ru/aspose.slides.export/ipdfoptions/
---

## Интерфейс IPdfOptions

Предоставляет опции, которые контролируют, как презентация сохраняется в формате Pdf.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа с пользовательским доступом. Смотрите [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Возвращает или устанавливает массив пользовательских имен семейств шрифтов, которые Aspose.Slides должен считать общими. Чтение/запись String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Применяет указанный прозрачный цвет к изображению, если `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Возвращает интерфейс ISaveOptions. Только для чтения [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Указывает, нужно ли автоматически выбирать наиболее эффективное сжатие (вместо стандартного) для каждого изображения. Если установлено Boolean.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведет к уменьшению размера результирующего PDF документа. Выбор лучшего соотношения сжатия изображений требует больших вычислительных ресурсов и занимает дополнительное количество оперативной памяти, и эта опция по умолчанию равна Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Желаемый уровень соответствия для генерируемого PDF документа. Чтение/запись [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Если true, рисует черную рамку вокруг каждого слайда. Чтение/запись Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Определяет, должны ли все символы шрифта быть встроены или только использовавшийся подмножество. Чтение/запись Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | Если true, встраивает шрифты TrueType для символов ASCII 32-127. Шрифты для кодов символов больше 127 всегда встраиваются. Чтение/запись Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Получает или устанавливает прозрачный цвет изображения. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | Если true, конвертирует все OLE данные из презентации в встроенные файлы в результирующем PDF. Чтение/запись Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Предоставляет опции, которые контролируют внешний вид объектов Ink в экспортированном документе. Только для чтения [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Возвращает или устанавливает значение, определяющее качество JPEG изображений внутри PDF документа. Чтение/запись Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Установка пароля пользователя для защиты PDF документа. Чтение/запись String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Указывает, следует ли растеризовать текст в виде битмапа и сохранять его в PDF, когда шрифт не поддерживает жирное начертание. Этот подход может улучшить качество текста в результирующем PDF для некоторых шрифтов. Чтение/запись Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | Если true, конвертирует все метафайлы, используемые в презентации, в изображения PNG. Чтение/запись Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Указывает, должен ли сгенерированный документ включать скрытые слайды. По умолчанию `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Получает или устанавливает режим, в котором слайды размещаются на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Возвращает или устанавливает значение, определяющее разрешение изображений внутри PDF документа. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Указывает тип сжатия, который следует использовать для всего текстового содержимого в документе. Чтение/запись [`PdfTextCompression`](../pdftextcompression). |

### См. Также

* интерфейс [ISaveOptions](../isaveoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->