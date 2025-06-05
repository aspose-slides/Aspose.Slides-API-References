---
title: SwfOptions
second_title: Aspose.Sildes для .NET API Справочник
description: Предоставляет параметры, которые контролируют, как презентация сохраняется в формате Swf.
type: docs
weight: 4340
url: /ru/aspose.slides.export/swfoptions/
---

## SwfOptions class

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SwfOptions](swfoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Указывает, нужно ли сжимать сгенерированный SWF-документ или нет. По умолчанию `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден. Читаемое-записываемое String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Включить/выключить контекстное меню. По умолчанию true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или задает визуальный стиль градиента. Читаемое-записываемое [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Указывает качество JPEG изображений. По умолчанию 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Изображение, которое будет отображаться как логотип в правом верхнем углу просмотрщика. Изображение должно быть PNG размером 32x64 пикселя, в противном случае логотип может отображаться неправильно. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Получает или задает полный гиперссылочный адрес для логотипа. Влияет только в том случае, если указан [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для обновлений процесса сохранения в процентном соотношении. См. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Показать/скрыть нижнюю панель. Может быть переопределено в flashvars. По умолчанию true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Показать/скрыть кнопку полноэкранного режима. Может быть переопределено в flashvars. По умолчанию true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Указывает, должен ли сгенерированный документ включать скрытые слайды или нет. По умолчанию `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Показать/скрыть левую панель. Может быть переопределено в flashvars. По умолчанию true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Указывает, должен ли отображаться бордер вокруг страниц. По умолчанию true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Показать/скрыть шаговый элемент страницы. Может быть переопределено в flashvars. По умолчанию true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Показать/скрыть раздел поиска. Может быть переопределено в flashvars. По умолчанию true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Показать/скрыть всю верхнюю панель. Может быть переопределено в flashvars. По умолчанию true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Читаемое-записываемое Boolean. Значение по умолчанию **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Получает или задает режим, в котором слайды располагаются на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). Это свойство не поддерживает присвоение объектов типа [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Начать с открытой левой панели. Может быть переопределено в flashvars. По умолчанию false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Указывает, должен ли сгенерированный SWF-документ включать встроенный просмотрщик документов или нет. По умолчанию `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. Читаемое-записываемое [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Примеры

Следующий пример показывает, как конвертировать PowerPoint в SWF Flash.

```csharp
[C#]
// Создать объект Presentation, представляющий файл презентации
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Сохранение презентации и страниц с заметками
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### См. также

* класс [SaveOptions](../saveoptions)
* интерфейс [ISwfOptions](../iswfoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->