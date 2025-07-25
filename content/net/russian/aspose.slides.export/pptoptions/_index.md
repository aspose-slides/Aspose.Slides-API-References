---
title: PptOptions
second_title: Aspose.Sildes для .NET API Справочник
description: Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате PPT.
type: docs
weight: 4170
url: /ru/aspose.slides.export/pptoptions/
---

## PptOptions class

Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате PPT.

```csharp
public class PptOptions : SaveOptions, IPptOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PptOptions](pptoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден. Свойство для чтения и записи String. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или задает визуальный стиль градиента. Свойство для чтения/записи [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для обновлений прогресса сохранения в процентах. См. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RootDirectoryClsid](../../aspose.slides.export/pptoptions/rootdirectoryclsid) { get; set; } | Представляет GUID (CLSID) класса объекта, который хранится в записи корневого каталога. Может использоваться для COM-активации приложения документа. Значение по умолчанию '64818D11-4F9B-11CF-86EA-00AA00B929E8', которое соответствует 'Microsoft Powerpoint.Slide.8'. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Свойство для чтения/записи Boolean. Значение по умолчанию - **false**. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. Свойство для чтения/записи [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Смотрите Также

* класс [SaveOptions](../saveoptions)
* интерфейс [IPptOptions](../ipptoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->