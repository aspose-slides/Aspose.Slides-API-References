---
title: IPdfOptions
second_title: Aspose.Sildes для .NET API Справочник
description: Предоставляет параметры, которые контролируют, как презентация сохраняется в формате Pdf.
type: docs
weight: 3830
url: /ru/aspose.slides.export/ipdfoptions/
---

## Интерфейс IPdfOptions

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате Pdf.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Содержит набор флагов, специфицирующих, какие разрешения доступа должны быть предоставлены при открытии документа с пользовательским доступом. См. [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Возвращает или устанавливает массив пользовательских имен семейств шрифтов, которые Aspose.Slides следует считать общими. Читаемое/записываемое `String[]`. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Применяет указанный прозрачный цвет к изображению, если `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Возвращает интерфейс ISaveOptions. Только для чтения [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Указывает, должен ли автоматически выбирать наиболее эффективный алгоритм сжатия (вместо значений по умолчанию) для каждого изображения. Если установлено в `Boolean.true`, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведет к меньшему размеру создаваемого PDF-документа. Выбор лучшего соотношения сжатия изображений требует больших вычислительных ресурсов и дополнительного объема ОЗУ, и по умолчанию эта опция равна `Boolean.false`. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Желательный уровень соответствия для создаваемого PDF-документа. Читаемое/записываемое [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | `True`, чтобы нарисовать черную рамку вокруг каждого слайда. Читаемое/записываемое `Boolean`. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Определяет, должны ли быть встроены все символы шрифта или только используемый подмножие. Читаемое/записываемое `Boolean`. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | `True`, чтобы встроить шрифты TrueType для символов ASCII 32-127. Шрифты для кодов символов, превышающих 127, всегда встраиваются. Читаемое/записываемое `Boolean`. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Получает или задает прозрачный цвет изображения. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | `True`, чтобы конвертировать все OLE-данные из презентации в встроенные файлы в результирующем PDF. Читаемое/записываемое `Boolean`. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Предоставляет опции, которые контролируют внешний вид объектов Ink в экспортированном документе. Только для чтения [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Возвращает или устанавливает значение, определяющее качество JPEG-изображений внутри PDF-документа. Читаемое/записываемое `Byte`. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Установка пользовательского пароля для защиты PDF-документа. Читаемое/записываемое `String`. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Указывает, должен ли текст растрироваться в виде битовой карты и сохраняться в PDF, когда шрифт не поддерживает жирное начертание. Этот подход может улучшить качество текста в конечном PDF для некоторых шрифтов. Читаемое/записываемое `Boolean`. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | `True`, чтобы конвертировать все метафайлы, используемые в презентации, в PNG-изображения. Читаемое/записываемое `Boolean`. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Указывает, должен ли сгенерированный документ включать скрытые слайды или нет. По умолчанию `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Получает или устанавливает режим, в котором слайды размещаются на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Возвращает или задает значение, определяющее разрешение изображений внутри PDF-документа. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Указывает тип сжатия, который будет использоваться для всего текстового содержимого документа. Читаемое/записываемое [`PdfTextCompression`](../pdftextcompression). |

### Смотрите также

* интерфейс [ISaveOptions](../isaveoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->