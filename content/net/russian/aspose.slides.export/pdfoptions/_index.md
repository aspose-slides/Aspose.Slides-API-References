---
title: PdfOptions
second_title: Aspose.Sildes для .NET API Reference
description: Предоставляет параметры, которые контролируют, как презентация сохраняется в формате Pdf.
type: docs
weight: 4140
url: /ru/aspose.slides.export/pdfoptions/
---

## Класс PdfOptions

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
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Содержит набор флагов, указывающих, какие разрешения доступа следует предоставить при открытии документа с пользовательским доступом. См. [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Возвращает или задает массив имен шрифтов, определенных пользователем, которые Aspose.Slides должен считать общими. Чтение/запись String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Применяет указанный прозрачный цвет к изображению, если `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Указывает, нужно ли автоматически выбирать наиболее эффективное сжатие (вместо стандартного) для каждого изображения. Если установлено в Boolean.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведет к меньшему размеру результирующего PDF-документа. Выбор наилучшего коэффициента сжатия изображений требует значительных вычислительных ресурсов и занимает дополнительное количество ОЗУ, и эта опция по умолчанию равна Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Желаемый уровень соответствия для создаваемого PDF-документа. Чтение/запись [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или задает шрифт, используемый в случае отсутствия исходного шрифта. Чтение/запись String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True, чтобы нарисовать черную рамку вокруг каждого слайда. Чтение/запись Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Определяет, должны ли быть встроены все символы шрифта или только используемый подмножий. Чтение/запись Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Определяет, будет ли Aspose.Slides встраивать общие шрифты для текста ASCII (диапазон кодов 33..127). Шрифты для символов с кодами больше 127 всегда встраиваются. Список общих шрифтов включает 14 базовых шрифтов PDF и дополнительные шрифты, указанные пользователем. Чтение/запись Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или устанавливает визуальный стиль градиента. Чтение/запись [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Получает или устанавливает прозрачный цвет изображения. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True, чтобы преобразовать все OLE-данные из презентации в встроенные файлы в результирующем PDF. Чтение/запись Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортированном документе. Только для чтения [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Возвращает или устанавливает значение, определяющее качество JPEG-изображений внутри PDF-документа. Чтение/запись Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Установка пользовательского пароля для защиты PDF-документа. Чтение/запись String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. См. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Указывает, должен ли текст быть растрирован как битмап и сохранен в PDF, если шрифт не поддерживает стиль полужирного начертания. Этот подход может улучшить качество текста в результирующем PDF для определенных шрифтов. Чтение/запись Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. Чтение/запись Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Указывает, следует ли включать скрытые слайды в создаваемый документ или нет. По умолчанию `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение/запись Boolean. Значение по умолчанию - **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Получает или устанавливает режим, в котором слайды размещаются на странице при экспортировании презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Возвращает или устанавливает значение, определяющее разрешение изображений внутри PDF-документа. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Указывает тип сжатия, который будет использоваться для всего текстового содержимого в документе. Чтение/запись [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или устанавливает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжаться или прервется. Чтение/запись [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Примеры

Следующий пример показывает, как преобразовать PowerPoint в PDF с пользовательскими параметрами.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Инициализация класса PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Устанавливает качество JPEG
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
// Инициализация класса Presentation, представляющего файл PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Инициализация класса PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Добавление скрытых слайдов
	pdfOptions.ShowHiddenSlides = true;
	// Сохраняет презентацию как PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Следующий пример показывает, как преобразовать PowerPoint в PDF с защитой паролем.

```csharp
[C#]
// Инициализация объекта Presentation, представляющего файл PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Инициализация класса PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Установка пароля PDF и разрешений доступа
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Сохраняет презентацию как PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Следующий пример показывает, как преобразовать PowerPoint в PDF с заметками.

```csharp
[C#]
// Инициализация объекта Presentation, представляющего файл презентации
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