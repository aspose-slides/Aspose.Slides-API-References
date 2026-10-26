---
title: SwfOptions
second_title: Aspose.Sildes для .NET – справочник API
description: Предоставляет параметры, управляющие тем, как презентация сохраняется в формате Swf.
type: docs
weight: 4530
url: /ru/aspose.slides.export/swfoptions/
---
## SwfOptions класс

Предоставляет параметры, управляющие тем, как презентация сохраняется в формате Swf.

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
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Указывает, следует ли сжимать сгенерированный документ SWF или нет. По умолчанию `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден. Чтение/запись String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Включает/отключает контекстное меню. По умолчанию `true`. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или задает визуальный стиль градиента. Чтение/запись [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Указывает качество JPEG-изображений. По умолчанию 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Изображение, которое будет отображаться как логотип в правом верхнем углу просмотрщика. Изображение должно быть PNG размером 32×64 пикселя, иначе логотип может отображаться некорректно. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Получает или задает полный адрес гиперссылки для логотипа. Имеет эффект только если указан [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для обновления прогресса сохранения в процентах. См. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Показывать/скрывать нижнюю панель. Может быть переопределено в flashvars. По умолчанию `true`. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Показывать/скрывать кнопку полноэкранного режима. Может быть переопределено в flashvars. По умолчанию `true`. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Указывает, следует ли включать скрытые слайды в сгенерированный документ. По умолчанию `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Показывать/скрывать левую панель. Может быть переопределено в flashvars. По умолчанию `true`. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Указывает, следует ли отображать границу вокруг страниц. По умолчанию `true`. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Показывать/скрывать переключатель страниц. Может быть переопределено в flashvars. По умолчанию `true`. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Показывать/скрывать раздел поиска. Может быть переопределено в flashvars. По умолчанию `true`. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Показывать/скрывать всю верхнюю панель. Может быть переопределено в flashvars. По умолчанию `true`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение/запись Boolean. Значение по умолчанию **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Получает или задает режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](../islideslayoutoptions). Это свойство не поддерживает присвоение объектов типа [`HandoutLayoutingOptions`](../handoutlayoutingoptions). |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Начинать с открытой левой панелью. Может быть переопределено в flashvars. По умолчанию `false`. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Указывает, следует ли включать интегрированный просмотрщик документа в сгенерированный SWF-документ. По умолчанию `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. Чтение/запись [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Примеры

Следующий пример показывает, как преобразовать PowerPoint в SWF Flash.

```csharp
[C#]
// Создать объект Presentation, который представляет файл презентации
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

### Смотрите также

* класс [SaveOptions](../saveoptions)
* интерфейс [ISwfOptions](../iswfoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->