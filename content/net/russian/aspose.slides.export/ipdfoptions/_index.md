---
title: IPdfOptions
second_title: Aspose.Sildes для .NET справочник API
description: Предоставляет параметры, контролирующие способ сохранения презентации в формате PDF.
type: docs
weight: 4020
url: /ru/aspose.slides.export/ipdfoptions/
---
## IPdfOptions интерфейс

Предоставляет параметры, контролирующие способ сохранения презентации в формате PDF.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. См. [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Возвращает или задаёт массив пользовательских имён семейств шрифтов, которые Aspose.Slides следует считать общими. Чтение/запись String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Применяет указанный прозрачный цвет к изображению, если `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Возвращает интерфейс ISaveOptions. Только для чтения [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо стандартного) для каждого изображения. Если установить в Boolean.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведёт к уменьшению размера получаемого PDF-документа. Выбор наилучшего коэффициента сжатия изображения требует значительных вычислительных ресурсов и дополнительной ОЗУ, и по умолчанию этот параметр установлен в Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Желаемый уровень соответствия для создаваемого PDF-документа. Чтение/запись [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True, чтобы рисовать чёрную рамку вокруг каждого слайда. Чтение/запись Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Определяет, следует ли встраивать все символы шрифта или только используемое подмножество. Чтение/запись Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True, чтобы встраивать шрифты TrueType для символов ASCII 32-127. Шрифты для кодов символов выше 127 всегда встраиваются. Чтение/запись Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Получает или задаёт прозрачный цвет изображения. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True, чтобы преобразовать все данные OLE из презентации во встраиваемые файлы в результирующем PDF. Чтение/запись Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Предоставляет параметры, управляющие отображением объектов Ink в экспортируемом документе. Только для чтения [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Возвращает или задаёт значение, определяющее качество JPEG-изображений в PDF-документе. Чтение/запись Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Установка пользовательского пароля для защиты PDF-документа. Чтение/запись String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Указывает, следует ли растрировать текст как bitmap и сохранять в PDF, если шрифт не поддерживает полужирное начертание. Такой подход может повысить качество текста в получаемом PDF для некоторых шрифтов. Чтение/запись Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True, чтобы преобразовать все метафайлы, использованные в презентации, в изображения PNG. Чтение/запись Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Указывает, должно ли создаваемый документ включать скрытые слайды. По умолчанию `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Получает или задаёт режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Возвращает или задаёт значение, определяющее разрешение изображений в PDF-документе. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Указывает тип сжатия, который будет использоваться для всего текстового содержимого документа. Чтение/запись [`PdfTextCompression`](../pdftextcompression). |

### См. также

* интерфейс [ISaveOptions](../isaveoptions)
* пространство имён [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->