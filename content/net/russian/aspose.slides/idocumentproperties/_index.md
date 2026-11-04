---
title: IDocumentProperties
second_title: Aspose.Sildes для .NET — справочник API
description: Представляет свойства презентации.
type: docs
weight: 5730
url: /ru/aspose.slides/idocumentproperties/
---
## IDocumentProperties интерфейс

Представляет свойства презентации.

```csharp
public interface IDocumentProperties
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Возвращает или задает шаблон приложения. Чтение/запись String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Возвращает версию приложения. Только для чтения String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Возвращает или задает автора презентации. Чтение/запись String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Возвращает или задает категорию презентации. Чтение/запись String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Возвращает или задает комментарии к презентации. Чтение/запись String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Возвращает или задает свойство компании. Чтение/запись String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Возвращает или задает статус содержимого презентации. Чтение/запись String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Возвращает или задает тип содержимого презентации. Чтение/запись String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Возвращает количество пользовательских свойств, фактически содержащихся в коллекции. Только для чтения Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Возвращает дату создания презентации. Значения указаны в UTC. Чтение/запись DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Указывает группировку частей документа и количество частей в каждой группе. Только для чтения IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Указывает количество скрытых слайдов в документе презентации. Только для чтения Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Возвращает или задает свойство документа HyperlinkBase. Чтение/запись String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий этот документ, обновит отношения гиперссылок новыми гиперссылками, указанными в этой части. Чтение/запись Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Возвращает или задает пользовательское свойство, связанное с указанным именем. Чтение/запись Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Возвращает или задает ключевые слова презентации. Чтение/запись String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Возвращает дату последней печати презентации. Чтение/запись DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Возвращает или задает имя последнего пользователя, изменившего презентацию. Чтение/запись String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Возвращает дату последнего изменения презентации. Значения указаны в UTC. Только для чтения в случае Presentation.DocumentProperties (поскольку она будет обновляться внутренне во время процесса сохранения объекта IPresentation). Может быть изменена через экземпляр DocumentProperties, возвращаемый методом [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Смотрите пример в сводке метода [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Возвращает или задает, актуальны ли гиперссылки в документе. Установите этот элемент в **true**, чтобы указать, что гиперссылки обновлены. Установите в **false**, чтобы указать, что гиперссылки устарели. Чтение/запись Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Возвращает или задает свойство менеджера. Чтение/запись String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Указывает общее количество звуковых или видеоклипов, присутствующих в документе. Только для чтения Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Возвращает или задает имя приложения. Чтение/запись String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Указывает количество слайдов в презентации, содержащих заметки. Только для чтения Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Указывает общее количество абзацев, найденных в документе, если применимо. Только для чтения Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Возвращает или задает целевой формат презентации. Чтение/запись String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Возвращает или задает номер ревизии презентации. Чтение/запись Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Указывает режим отображения миниатюры документа. Установите этот элемент в **true**, чтобы включить масштабирование миниатюры документа под дисплей. Установите этот элемент в **false**, чтобы включить обрезку миниатюры документа, отображая только те части, которые помещаются в дисплей. Чтение/запись Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Определяет, общая ли презентация между несколькими пользователями. Чтение/запись Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Указывает общее количество слайдов в документе презентации. Только для чтения Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Возвращает или задает тему презентации. Чтение/запись String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Возвращает или задает заголовок презентации. Чтение/запись String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Указывает заголовок каждой части документа. Эти части не являются частями документа, а являются концептуальными представлениями разделов документа. Только для чтения string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Общее время редактирования презентации. Чтение/запись TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Указывает общее количество слов, содержащихся в документе. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Очищает и задает значения по умолчанию для всех встроенных свойств. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Удаляет все пользовательские свойства. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Проверяет наличие пользовательского свойства с указанным именем. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Возвращает имя пользовательского свойства по указанному индексу. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Получает именованное логическое значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Получает именованное значение DateTime из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Получает именованное значение double из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Получает именованное значение float из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Получает именованное целочисленное значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Получает именованное строковое значение из пользовательских свойств. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Получает массив меток чувствительности из пользовательских свойств документа (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Удаляет пользовательское свойство, связанное с указанным именем. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Задает именованное логическое пользовательское свойство. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Задает именованное пользовательское свойство DateTime. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Задает именованное пользовательское свойство double. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Задает именованное пользовательское свойство float. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Задает именованное целочисленное пользовательское свойство. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Задает именованное строковое пользовательское свойство. |

### См. также

* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->