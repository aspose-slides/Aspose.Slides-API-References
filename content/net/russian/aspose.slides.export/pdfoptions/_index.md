---
title: PdfOptions
second_title: Aspose.Sildes для .NET: справочник API
description: Предоставляет параметры, управляющие тем, как презентация сохраняется в формате PDF.
type: docs
weight: 4350
url: /ru/aspose.slides.export/pdfoptions/
---
## PdfOptions класс

Provides options that control how a presentation is saved in Pdf format.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfOptions](pdfoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа с пользовательским доступом. См. [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Возвращает или задает массив пользовательских имен семейств шрифтов, которые Aspose.Slides должен считать общими. Чтение/запись String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Применяет заданный прозрачный цвет к изображению, если `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо используемого по умолчанию) для каждого изображения. Если установлено Boolean.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведёт к меньшему размеру получаемого PDF-документа. Выбор лучшего коэффициента сжатия изображений ресурсоёмок и требует дополнительной оперативной памяти; по умолчанию эта опция имеет значение Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Желаемый уровень соответствия генерируемого PDF-документа. Чтение/запись [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден. Чтение/запись String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True, чтобы рисовать черную рамку вокруг каждого слайда. Чтение/запись Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Определяет, следует ли встраивать все символы шрифта или только используемую подсетку. Чтение/запись Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Определяет, будет ли Aspose.Slides встраивать общие шрифты для текста ASCII (диапазон кодов 33..127). Шрифты для кодов символов больше 127 всегда встраиваются. Список общих шрифтов включает базовые 14 шрифтов PDF и дополнительные пользовательские шрифты. Чтение/запись Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или задает визуальный стиль градиента. Чтение/запись [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Получает или задает прозрачный цвет изображения. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True, если необходимо преобразовать все данные OLE из презентации во встроенные файлы в результирующий PDF. Чтение/запись Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе. Только для чтения [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Возвращает или задает значение, определяющее качество JPEG-изображений в PDF-документе. Чтение/запись Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Установка пароля пользователя для защиты PDF-документа. Чтение/запись String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для обновлений процесса сохранения в процентах. См. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Указывает, следует ли растеризовать текст как растровое изображение и сохранять в PDF, если шрифт не поддерживает полужирное начертание. Этот подход может улучшить качество текста в результирующем PDF для некоторых шрифтов. Чтение/запись Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True, если необходимо преобразовать все метафайлы, использованные в презентации, в изображения PNG. Чтение/запись Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Указывает, должен ли сгенерированный документ включать скрытые слайды. По умолчанию `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение/запись Boolean. Значение по умолчанию **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Получает или задает режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Возвращает или задает значение, определяющее разрешение изображений в PDF-документе. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Указывает тип сжатия, используемый для всего текстового содержимого документа. Чтение/запись [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или задает объект, получающий предупреждения и решающий, продолжить ли процесс загрузки или прервать его. Чтение/запись [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Примеры

Следующий пример демонстрирует, как преобразовать PowerPoint в PDF с пользовательскими параметрами.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Создает экземпляр класса PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Устанавливает качество JPEG
	pdfOptions.JpegQuality = 90;
	// Устанавливает поведение для метафайлов
	pdfOptions.SaveMetafilesAsPng = true;
	// Устанавливает уровень сжатия текста
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Определяет стандарт PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Сохраняет презентацию в PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Следующий пример демонстрирует, как преобразовать PowerPoint в PDF с учётом скрытых слайдов.

```csharp
[C#]
// Создает экземпляр класса Presentation, представляющего файл PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Создает экземпляр класса PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Добавляет скрытые слайды
	pdfOptions.ShowHiddenSlides = true;
	// Сохраняет презентацию в PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Следующий пример демонстрирует, как преобразовать PowerPoint в PDF, защищённый паролем.

```csharp
[C#]
// Создает объект Presentation, представляющий файл PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Создает экземпляр класса PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Устанавливает пароль PDF и разрешения доступа
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Сохраняет презентацию в PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Следующий пример демонстрирует, как преобразовать PowerPoint в PDF с заметками.

```csharp
[C#]
// Создает объект Presentation, представляющий файл презентации
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

* класс [SaveOptions](../saveoptions)
* интерфейс [IPdfOptions](../ipdfoptions)
* пространство имён [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->