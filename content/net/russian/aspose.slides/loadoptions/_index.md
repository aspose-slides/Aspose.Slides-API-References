---
title: LoadOptions
second_title: Aspose.Slides для .NET API Справочник
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

| Название | Описание |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Создает новые параметры загрузки по умолчанию. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Создает новые параметры загрузки. |

## Свойства

| Название | Описание |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Представляет параметры, которые могут использоваться для управления поведением обработки бинарных больших объектов (BLOB), такими как использование временных файлов или максимальное количество байт BLOB в памяти. Эти параметры предназначены для настройки наилучшего соотношения производительности и потребления памяти для конкретной среды или требований. Бинарный большой объект (BLOB) – это бинарные данные, хранимые как единое целое – т.е. BLOB может быть аудио, видео или самой презентацией. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Возвращает или устанавливает азиатский шрифт, используемый в случае, если исходный шрифт не найден. Чтение/запись String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Возвращает или устанавливает основной шрифт, используемый в случае, если исходный шрифт не найден. Чтение/запись String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Возвращает или устанавливает символический шрифт, используемый в случае, если исходный шрифт не найден. Чтение/запись String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Возвращает или устанавливает язык по умолчанию для текста презентации. Чтение/запись String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Определяет, будет ли Aspose.Slides удалять все встроенные бинарные объекты во время загрузки презентации. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Указывает источники внешних шрифтов, которые будут использоваться презентацией. Эти шрифты доступны презентации на протяжении всей её жизни и не делятся с другими презентациями. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Токен для мониторинга запросов на прерывание. Этот токен управляет сроком жизни всего экземпляра [`IPresentation`](../ipresentation). Любая длительная операция, такая как загрузка или сохранение презентации, будет прервана через вызов метода [`Interrupt`](../interruptiontokensource/interrupt) класса [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Возвращает или устанавливает формат загружаемой презентации. Чтение/запись [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Это свойство имеет смысл, если файл презентации защищен паролем. Значение true означает, что должны быть загружены только свойства документа из зашифрованного файла презентации, и пароль должен быть проигнорирован. Значение false означает, что вся зашифрованная презентация должна быть загружена с использованием правильного пароля. Если презентация не зашифрована, то значение свойства всегда игнорируется. Если свойства документа зашифрованного файла не являются общедоступными и значение свойства true, то свойства документа не могут быть загружены, и будет выдано исключение. Чтение/запись Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Получает или устанавливает пароль. Чтение/запись String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Возвращает или устанавливает интерфейс обратного вызова, который управляет загрузкой внешних ресурсов. Чтение/запись [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Получает параметры для электронных таблиц. Например, эти параметры влияют на вычисление формул для диаграмм. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Возвращает или устанавливает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжаться или будет прерван. Чтение/запись [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### См. также

* интерфейс [ILoadOptions](../iloadoptions)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->