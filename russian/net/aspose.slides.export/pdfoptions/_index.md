---
title: PdfOptions
second_title: Справочник по API Aspose.Slides для .NET
description: Предоставляет параметры управляющие сохранением презентации в формате Pdf.
type: docs
weight: 3930
url: /ru/net/aspose.slides.export/pdfoptions/
---
## PdfOptions class

Предоставляет параметры, управляющие сохранением презентации в формате Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfOptions](pdfoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Содержит набор флагов, указывающих, какие права доступа должны быть предоставлены при открытии документа с доступом пользователя. Видеть[`PdfAccessPermissions`](../pdfaccesspermissions) . |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Возвращает или задает массив определяемых пользователем имен семейств шрифтов, которые Aspose.Slides должен считать общими. Чтение/записьString []. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Применяет указанный прозрачный цвет к изображению, если`истинный` . |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Указывает, должно ли наиболее эффективное сжатие (вместо стандартного) для каждого изображения выбираться автоматически. Если установленоBoolean.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия , что приведет к уменьшению размера итогового документа PDF.  Выбор наилучшего коэффициента сжатия изображения требует больших вычислительных ресурсов и требует дополнительного объема ОЗУ, поэтому этот параметрBoolean.false по умолчанию. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Желаемый уровень соответствия для созданного документа PDF. Чтение/запись[`PdfCompliance`](../pdfcompliance) . |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Чтение-записьString . |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True для рисования черной рамки вокруг каждого слайда. Чтение/записьBoolean . |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Определяет, должны ли быть встроены все символы шрифта или используется только подмножество. Чтение/записьBoolean . |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Определяет, будет ли Aspose.Slides встраивать общие шрифты для текста ASCII (диапазон кодов 33..127). Шрифты для кодов символов больше 127 всегда встраиваются. Читай пишиBoolean . |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Получает или задает прозрачный цвет изображения. |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Возвращает или задает значение, определяющее качество изображений JPEG внутри документа PDF. Чтение/записьByte . |
| [NotesCommentsLayouting](../../aspose.slides.export/pdfoptions/notescommentslayouting) { get; } | Предоставляет параметры, управляющие размещением примечаний и комментариев в экспортируемом документе. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Установка пароля пользователя для защиты документа PDF. Чтение/записьString . |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для сохранения обновлений хода выполнения в процентах. См.[`IProgressCallback`](../../aspose.slides/iprogresscallback) . |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | Значение true для преобразования всех метафайлов, используемых в презентации, в изображения PNG. Чтение/записьBoolean . |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Указывает, должен ли сгенерированный документ включать скрытые слайды или нет. Значение по умолчанию:`ЛОЖЬ` |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Возвращает или задает значение, определяющее разрешение изображений внутри документа PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Указывает тип сжатия, который будет использоваться для всего текстового содержимого в документе. Чтение/запись[`PdfTextCompression`](../pdftextcompression) . |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает наборы объекта, который получает предупреждения и решает, будет ли процесс загрузки продолжен или будет прерван. Чтение/запись[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Смотрите также

* class [SaveOptions](../saveoptions)
* interface [IPdfOptions](../ipdfoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
