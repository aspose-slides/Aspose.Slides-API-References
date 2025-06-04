---
title: PdfOptions
second_title: Aspose.Sildes для .NET API Справочник
description: Предоставляет параметры, которые контролируют, как презентация сохраняется в формате Pdf.
type: docs
weight: 4140
url: /ru/aspose.slides.export/pdfoptions/
---

## PdfOptions class

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [PdfOptions](pdfoptions)() | Конструктор по умолчанию. |

## Свойства

| Название | Описание |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа с пользовательским доступом. См. [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Возвращает или устанавливает массив пользовательских имен семейств шрифтов, которые Aspose.Slides должен считать обычными. Чтение/запись String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Применяет указанный прозрачный цвет к изображению, если `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Указывает, нужно ли автоматически выбирать наиболее эффективное сжатие (вместо исходного) для каждого изображения. Если установлено значение Boolean.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведет к меньшему размеру итогового PDF-документа. Выбор лучшего коэффициента сжатия изображения является ресурсоемким и требует дополнительного объема ОЗУ, а этот параметр по умолчанию установлен на Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Желаемый уровень соответствия для создаваемого PDF-документа. Чтение/запись [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Чтение/запись String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True для рисования черной рамки вокруг каждого слайда. Чтение/запись Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Определяет, должны ли все символы шрифта быть встроены или только используемая подсекция. Чтение/запись Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Определяет, будет ли Aspose.Slides встраивать общие шрифты для текста ASCII (кодовый диапазон 33..127). Шрифты для кодов символов больше 127 всегда встраиваются. Список общих шрифтов включает базовые шрифты PDF 14 и дополнительные шрифты, указанные пользователем. Чтение/запись Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или устанавливает визуальный стиль градиента. Чтение/запись [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Получает или устанавливает прозрачный цвет изображения. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True для преобразования всех OLE-данных из презентации в встроенные файлы в результирующем PDF. Чтение/запись Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортированном документе. Только для чтения [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Возвращает или устанавливает значение, определяющее качество JPEG-изображений внутри PDF-документа. Чтение/запись Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Установка пароля пользователя для защиты PDF-документа. Чтение/запись String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для обновления прогресса сохранения в процентах. См. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Указывает, следует ли растеризовать текст в растровый формат и сохранить в PDF, если шрифт не поддерживает жирное начертание. Этот подход может улучшить качество текста в результирующем PDF для определенных шрифтов. Чтение/запись Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True для преобразования всех метафайлов, использованных в презентации, в PNG-изображения. Чтение/запись Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Указывает, должна ли создаваемая документация включать скрытые слайды или нет. По умолчанию `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение/запись Boolean. Значение по умолчанию — **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Получает или устанавливает режим, в котором слайды размещаются на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Возвращает или устанавливает значение, определяющее разрешение изображений внутри PDF-документа. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Указывает тип сжатия, который будет использоваться для всего текстового контента в документе. Чтение/запись [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или устанавливает объект, который получает предупреждения и решает, будет ли продолжен процесс загрузки или будет прерван. Чтение/запись [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Примеры

Следующий пример показывает, как преобразовать PowerPoint в PDF с пользовательскими параметрами.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Создает экземпляр класса PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Устанавливает качество Jpeg
	pdfOptions.JpegQuality = 90;
	// Устанавливает поведение для метафайлов
	pdfOptions.SaveMetafilesAsPng = true;
	// Устанавливает уровень сжатия текста
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Определяет стандарт PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Сохраняет презентацию как PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Следующий пример показывает, как преобразовать PowerPoint в PDF с скрытыми слайдами.

```csharp
[C#]
// Создает экземпляр класса Presentation, который представляет файл PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Создает экземпляр класса PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Добавляет скрытые слайды
	pdfOptions.ShowHiddenSlides = true;
	// Сохраняет презентацию как PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Следующий пример показывает, как преобразовать PowerPoint в защищенный паролем PDF.

```csharp
[C#]
// Создает экземпляр объекта Presentation, который представляет файл PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Создает экземпляр класса PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Устанавливает пароль PDF и разрешения доступа
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Сохраняет презентацию как PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Следующий пример показывает, как преобразовать PowerPoint в PDF с заметками.

```csharp
[C#]
// Создает экземпляр объекта Presentation, который представляет файл презентации
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Установка типа и размера слайда
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### См. также

* класс [SaveOptions](../saveoptions)
* интерфейс [IPdfOptions](../ipdfoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
