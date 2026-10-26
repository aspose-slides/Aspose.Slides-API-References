---
title: IPdfOptions
second_title: Aspose.Sildes для .NET справка API
description: Предоставляет параметры, управляющие тем, как презентация сохраняется в формате PDF.
type: docs
weight: 4000
url: /ru/aspose.slides.export/ipdfoptions/
---
## IPdfOptions интерфейс

Предоставляет параметры, управляющие тем, как презентация сохраняется в формате PDF.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. См. [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Возвращает или задаёт массив пользовательских названий семейств шрифтов, которые Aspose.Slides должен считать общими. Чтение/запись String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Применяет указанный прозрачный цвет к изображению, если `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Возвращает интерфейс ISaveOptions. Только для чтения [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо стандартного) для каждого изображения. Если установлено в Boolean.true, для каждого изображения в презентации будет выбран наилучший алгоритм сжатия, что приведёт к меньшему размеру получаемого PDF-документа. Выбор лучшего отношения сжатия изображений требует значительных вычислительных ресурсов и дополнительной ОЗУ, а по умолчанию этот параметр имеет значение Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Желаемый уровень соответствия генерируемого PDF-документа. Чтение/запись [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True, если нужно рисовать черную рамку вокруг каждого слайда. Чтение/запись Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Определяет, должны ли быть встроены все символы шрифта или только используемое подмножество. Чтение/запись Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True, если следует встраивать TrueType-шрифты для символов ASCII 32-127. Шрифты для кодов символов больше 127 всегда встраиваются. Чтение/запись Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Получает или задаёт прозрачный цвет изображения. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True, если необходимо преобразовать все OLE-данные из презентации во вложенные файлы в результирующем PDF. Чтение/запись Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе. Только для чтения [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Возвращает или задаёт значение, определяющее качество JPEG-изображений в PDF-документе. Чтение/запись Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Устанавливает пользовательский пароль для защиты PDF-документа. Чтение/запись String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Указывает, следует ли растеризовать текст как bitmap и сохранить в PDF, если шрифт не поддерживает полужирное начертание. Этот подход может улучшить качество текста в результирующем PDF для некоторых шрифтов. Чтение/запись Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True, если необходимо преобразовать все метафайлы, использованные в презентации, в изображения PNG. Чтение/запись Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Указывает, должен ли генерируемый документ включать скрытые слайды. По умолчанию `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Получает или задаёт режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Возвращает или задаёт значение, определяющее разрешение изображений в PDF-документе. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Указывает тип сжатия, используемый для всего текстового содержимого в документе. Чтение/запись [`PdfTextCompression`](../pdftextcompression). |

### Смотрите также

* интерфейс [ISaveOptions](../isaveoptions)
* пространство имён [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->