---
title: ILoadOptions
second_title: Справочник по API Aspose.Slides для .NET
description: Позволяет указать дополнительные параметры например формат или шрифт по умолчанию при загрузке презентации.
type: docs
weight: 5780
url: /ru/aspose.slides/iloadoptions/
---
## ILoadOptions interface

Позволяет указать дополнительные параметры (например, формат или шрифт по умолчанию) при загрузке презентации.

```csharp
public interface ILoadOptions
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Представляет параметры, которые можно использовать для управления поведением обработки больших двоичных объектов (BLOB), например, использование временных файлов или максимальное количество байтов BLOB. в памяти. Эти параметры предназначены для установки наилучшего соотношения производительности и потребления памяти для конкретной среды или требований.  Большой двоичный объект (BLOB) представляет собой двоичные данные, хранящиеся как единое целое, т.е. BLOB может быть аудио, видео или самой презентацией . |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Возвращает или устанавливает азиатский шрифт, используемый в случае, если исходный шрифт не найден. Чтение-записьString. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Возвращает или устанавливает обычный шрифт, используемый в случае, если исходный шрифт не найден. Чтение-записьString. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Возвращает или устанавливает символьный шрифт, используемый в случае, если исходный шрифт не найден. Чтение-записьString. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Указывает источники внешних шрифтов, которые будут использоваться презентацией. Эти шрифты доступны для презентации в течение всего времени ее существования и не используются совместно с другими презентациями |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Маркер для отслеживания запросов прерывания.  Этот токен управляет всем[`IPresentation`](../ipresentation)временем существования экземпляра. Любая длительная операция, такая как презентация загрузка или сохранение, будет прервана вызовом метода[`Interrupt`](../iinterruptiontokensource/interrupt) the[`IInterruptionTokenSource`](../iinterruptiontokensource). |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Возвращает или задает формат загружаемой презентации. Чтение/запись[`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Это свойство имеет смысл, если файл презентации защищен паролем. Значение true означает, что из зашифрованного файла презентации должны быть загружены только свойства документа, а пароль должен игнорироваться. Значение false означает, что вся зашифрованная презентация должна загружаться с использованием правильного пароля. Если презентация не зашифрована, то значение свойства всегда игнорируется. Если свойства документа зашифрованного файла не являются общедоступными и значение свойства равно true, то свойства документа не могут быть загружены, и будет выдано исключение. Чтение-записьBoolean. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Получает или задает пароль. Чтение-записьString. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Возвращает или задает интерфейс обратного вызова, управляющий загрузкой внешних ресурсов. Чтение/запись[`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Представляет параметры, которые можно использовать для указания дополнительного поведения электронных таблиц. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Возвращает или устанавливает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. Чтение/запись[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
