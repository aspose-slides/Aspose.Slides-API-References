---
title: XpsOptions
second_title: Aspose.Sildes для .NET API Справочник
description: Предоставляет параметры, которые контролируют, как презентация сохраняется в формате XPS.
type: docs
weight: 4540
url: /ru/aspose.slides.export/xpsoptions/
---

## Класс XpsOptions

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате XPS.

```csharp
public class XpsOptions : SaveOptions, IXpsOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XpsOptions](xpsoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден. Читаемая и записываемая строка. |
| [DrawSlidesFrame](../../aspose.slides.export/xpsoptions/drawslidesframe) { get; set; } | Истина, чтобы нарисовать черную рамку вокруг каждого слайда. Читаемое/записываемое логическое значение. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или устанавливает визуальный стиль градиента. Читаемое/записываемое [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для обновления прогресса сохранения в процентах. См. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [SaveMetafilesAsPng](../../aspose.slides.export/xpsoptions/savemetafilesaspng) { get; set; } | Истина, чтобы конвертировать все метафайлы, используемые в презентации, в изображения PNG. Читаемое/записываемое логическое значение. |
| [ShowHiddenSlides](../../aspose.slides.export/xpsoptions/showhiddenslides) { get; set; } | Указывает, следует ли включать скрытые слайды в сгенерированный документ или нет. По умолчанию `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Читаемое/записываемое логическое значение. Значение по умолчанию — **false**. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или задает объект, который получает предупреждения и решает, продолжится ли процесс загрузки или будет прерван. Читаемое/записываемое [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Примеры

Следующий пример показывает, как конвертировать презентации в XPS, используя настройки по умолчанию.

```csharp
[C#]
// Создайте объект Presentation, который представляет файл презентации
using (Presentation pres = new Presentation("Convert_XPS.pptx"))
{
    // Сохраните презентацию в документ XPS
    pres.Save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
}
```

Следующий пример показывает, как конвертировать презентации в XPS, используя пользовательские настройки.

```csharp
[C#]
// Создайте объект Presentation, который представляет файл презентации
using (Presentation pres = new Presentation("Convert_XPS_Options.pptx"))
{
    // Создайте класс XpsOptions
    XpsOptions options = new XpsOptions();
    // Сохранить метафайлы как PNG
    options.SaveMetafilesAsPng = true;
    // Сохраните презентацию в документ XPS
    pres.Save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
}
```

### См. также

* класс [SaveOptions](../saveoptions)
* интерфейс [IXpsOptions](../ixpsoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->