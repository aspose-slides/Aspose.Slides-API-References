---
title: ILoadOptions
second_title: Справочник по API Aspose.Slides для .NET
description: Позволяет указать дополнительные параметры например формат или шрифт по умолчанию при загрузке презентации.
type: docs
weight: 5780
url: /ru/net/aspose.slides/iloadoptions/
---
## ILoadOptions interface

Позволяет указать дополнительные параметры (например, формат или шрифт по умолчанию) при загрузке презентации.

```csharp
public interface ILoadOptions
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Представляет параметры, которые можно использовать для управления поведением обработки больших двоичных объектов (BLOB), , таких как использование временных файлов или максимальное количество байтов BLOB в памяти. Эти параметры предназначены для настройки наилучшего соотношения производительности и потребления памяти для конкретной среды или требований. Большой двоичный объект (BLOB) — это двоичные данные, хранящиеся как единый объект, т. е. BLOB может быть аудио, видео или презентацией. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Возвращает или задает азиатский шрифт, используемый в случае, если исходный шрифт не найден. Чтение-записьString . |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Возвращает или задает обычный шрифт, используемый в случае, если исходный шрифт не найден. Чтение-записьString . |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Возвращает или задает шрифт символов, используемый в случае, если исходный шрифт не найден. Чтение-записьString . |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Указывает источники внешних шрифтов, которые будут использоваться презентацией. Эти шрифты доступны для презентации в течение всего времени ее существования и не используются совместно с другими презентациями |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Маркер для отслеживания запросов прерывания.  Этот токен управляет всем[`IPresentation`](../ipresentation) время жизни экземпляра. Любая длительная операция, такая как загрузка или сохранение презентации , будет прервана вызовом функции[`Interrupt`](../iinterruptiontokensource/interrupt) метод [`IInterruptionTokenSource`](../iinterruptiontokensource) . |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Возвращает или задает формат презентации для загрузки. Чтение/запись[`LoadFormat`](../loadformat) . |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Это свойство имеет смысл, если файл презентации защищен паролем. Значение true означает, что из зашифрованного файла презентации должны быть загружены только свойства документа, а пароль должен игнорироваться. Значение false означает, что вся зашифрованная презентация должна быть загружена с использование правильного пароля. Если презентация не зашифрована, то значение свойства всегда игнорируется. Если свойства документа зашифрованного файла не являются общедоступными и значение свойства равно true, то свойства документа не могут быть загружены, и будет выдано исключение. Читай пишиBoolean . |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Получает или устанавливает пароль. Чтение-записьString . |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Возвращает или задает интерфейс обратного вызова, который управляет загрузкой внешних ресурсов. Чтение/запись[`IResourceLoadingCallback`](../iresourceloadingcallback) . |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Представляет параметры, которые можно использовать для указания дополнительного поведения электронных таблиц. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или будет прерван. Чтение/запись[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
