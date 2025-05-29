---
title: LoadOptions
second_title: Aspose.Slides для .NET Справочник по API
description: Позволяет указать дополнительные параметры, такие как формат или шрифт по умолчанию при загрузке презентации.
type: docs
weight: 7600
url: /ru/aspose.slides/loadoptions/
---

## Класс LoadOptions

Позволяет указать дополнительные параметры (такие как формат или шрифт по умолчанию) при загрузке презентации.

```csharp
public class LoadOptions : ILoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Создает новые параметры загрузки по умолчанию. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Создает новые параметры загрузки. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Представляет параметры, которые могут быть использованы для управления поведением обработки больших двоичных объектов (BLOB), такими как использование временных файлов или максимальное количество байт BLOB в памяти. Эти параметры предназначены для настройки лучшего соотношения производительности к потреблению памяти для конкретной среды или требований. Большой двоичный объект (BLOB) — это двоичные данные, хранящиеся как единое целое — т.е. BLOB может быть аудио, видео или самой презентацией. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Возвращает или задает азиатский шрифт, используемый в случае отсутствия исходного шрифта. Чтение/запись Строка. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Возвращает или задает обычный шрифт, используемый в случае отсутствия исходного шрифта. Чтение/запись Строка. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Возвращает или задает символ шрифта, используемый в случае отсутствия исходного шрифта. Чтение/запись Строка. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Возвращает или задает язык по умолчанию для текста презентации. Чтение/запись Строка. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Определяет, будет ли Aspose.Slides удалять все встроенные двоичные объекты при загрузке презентации. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Указывает источники внешних шрифтов, которые будут использоваться в презентации. Эти шрифты доступны для презентации на протяжении ее жизни и не разделяются с другими презентациями. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Токен для отслеживания запросов на прерывание. Этот токен управляет всей жизнью экземпляра [`IPresentation`](../ipresentation). Любая длительная операция, такая как загрузка или сохранение презентации, будет прервана путем вызова метода [`Interrupt`](../interruptiontokensource/interrupt) класса [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Возвращает или задает формат презентации для загрузки. Чтение/запись [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Это свойство имеет смысл, если файл презентации защищен паролем. Значение true означает, что должны быть загружены только свойства документа из зашифрованного файла презентации, а пароль должен быть проигнорирован. Значение false означает, что вся зашифрованная презентация должна быть загружена с использованием правильного пароля. Если презентация не зашифрована, то значение свойства всегда игнорируется. Если свойства документа зашифрованного файла не являются публичными, и значение свойства true, то свойства документа не могут быть загружены, и будет выброшено исключение. Чтение/запись Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Получает или устанавливает пароль. Чтение/запись Строка. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Возвращает или задает интерфейс обратного вызова, который управляет загрузкой внешних ресурсов. Чтение/запись [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Получает параметры для электронных таблиц. Например, эти параметры влияют на вычисление формул для диаграмм. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжаться или будет прерван. Чтение/запись [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Смотрите также

* интерфейс [ILoadOptions](../iloadoptions)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->