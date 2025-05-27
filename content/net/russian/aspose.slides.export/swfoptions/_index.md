---
title: SwfOptions
second_title: Aspose.Sildes для .NET API Справочник
description: Предоставляет параметры, которые контролируют, как презентация сохраняется в формате Swf.
type: docs
weight: 4340
url: /ru/aspose.slides.export/swfoptions/
---

## Класс SwfOptions

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [SwfOptions](swfoptions)() | Конструктор по умолчанию. |

## Свойства

| Название | Описание |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Указывает, следует ли сжимать сгенерированный документ SWF или нет. По умолчанию `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или устанавливает шрифт, используемый в случае отсутствия исходного шрифта. Читаемо-записываемая строка. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Включить/выключить контекстное меню. По умолчанию true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или устанавливает визуальный стиль градиента. Читаемо/записываемый [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Указывает качество JPEG изображений. По умолчанию 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Изображение, которое будет отображаться в качестве логотипа в правом верхнем углу просмотрщика. Изображение должно быть PNG размером 32x64 пикселя, в противном случае логотип может отображаться неправильно. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Получает или устанавливает полный адрес гиперссылки для логотипа. У оказывает влияние только если указан [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для обновления прогресса сохранения в процентах. См. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Показать/скрыть нижнюю панель. Может быть переопределено в flashvars. По умолчанию true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Показать/скрыть кнопку развертывания на весь экран. Может быть переопределено в flashvars. По умолчанию true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Указывает, следует ли включать в сгенерированный документ скрытые слайды. По умолчанию `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Показать/скрыть левую панель. Может быть переопределено в flashvars. По умолчанию true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Указывает, следует ли показывать границу вокруг страниц. По умолчанию true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Показать/скрыть шаги страниц. Может быть переопределено в flashvars. По умолчанию true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Показать/скрыть раздел поиска. Может быть переопределено в flashvars. По умолчанию true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Показать/скрыть всю верхнюю панель. Может быть переопределено в flashvars. По умолчанию true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Читаемо/записываемый булев тип. Значение по умолчанию - **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Получает или устанавливает режим, в котором слайды располагаются на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). Это свойство не поддерживает присваивание объектов типа [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Начать с открытой левой панели. Может быть переопределено в flashvars. По умолчанию false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Указывает, следует ли включать в сгенерированный документ SWF встроенный просмотрщик документа или нет. По умолчанию `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или устанавливает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. Читаемо/записываемый [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Примеры

Следующий пример показывает, как конвертировать PowerPoint в SWF Flash.

```csharp
[C#]
// Создание объекта Presentation, представляющего файл презентации
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Сохранение презентации и страниц заметок
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Смотрите Также

* класс [SaveOptions](../saveoptions)
* интерфейс [ISwfOptions](../iswfoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->