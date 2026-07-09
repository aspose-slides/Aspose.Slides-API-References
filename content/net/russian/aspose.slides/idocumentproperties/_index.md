---
title: IDocumentProperties
second_title: Aspose.Sildes для .NET справочник API
description: Представляет свойства презентации.
type: docs
weight: 5710
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
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Возвращает версию приложения. Только чтение String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Возвращает или задает автора презентации. Чтение/запись String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Возвращает или задает категорию презентации. Чтение/запись String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Возвращает или задает комментарии презентации. Чтение/запись String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Возвращает или задает свойство компании. Чтение/запись String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Возвращает или задает статус содержимого презентации. Чтение/запись String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Возвращает или задает тип содержимого презентации. Чтение/запись String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Возвращает количество пользовательских свойств, фактически содержащихся в коллекции. Только чтение Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Возвращает дату создания презентации. Значения в UTC. Чтение/запись DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Указывает группировку частей документа и количество частей в каждой группе. Только чтение IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Определяет количество скрытых слайдов в документе презентации. Только чтение Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Возвращает или задает свойство документа HyperlinkBase. Чтение/запись String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий документ, должен обновить отношения гиперссылок новыми гиперссылками, указанными в этой части. Чтение/запись Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Возвращает или задает пользовательское свойство, связанное с указанным именем. Чтение/запись Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Возвращает или задает ключевые слова презентации. Чтение/запись String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Возвращает дату последней печати презентации. Чтение/запись DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Возвращает или задает имя последнего человека, изменившего презентацию. Чтение/запись String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Возвращает дату последнего изменения презентации. Значения в UTC. Только чтение в случае Presentation.DocumentProperties (поскольку он будет обновляться внутренне во время процесса сохранения объекта IPresentation). Может быть изменено через экземпляр DocumentProperties, возвращаемый методом [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). См. пример в методе [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Указывает, актуальны ли гиперссылки в документе. Установите элемент в **true**, чтобы указать, что гиперссылки обновлены. Установите элемент в **false**, чтобы указать, что гиперссылки устарели. Чтение/запись Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Возвращает или задает свойство менеджера. Чтение/запись String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Указывает общее количество звуковых или видеоклипов, присутствующих в документе. Только чтение Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Возвращает или задает имя приложения. Чтение/запись String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Указывает количество слайдов в презентации, содержащих заметки. Только чтение Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Указывает общее количество абзацев, найденных в документе, если применимо. Только чтение Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Возвращает или задает предполагаемый формат презентации. Чтение/запись String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Возвращает или задает номер ревизии презентации. Чтение/запись Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Указывает режим отображения миниатюры документа. Установите элемент в **true**, чтобы включить масштабирование миниатюры документа под дисплей. Установите элемент в **false**, чтобы включить обрезку миниатюры документа, показывая только те части, которые помещаются на дисплей. Чтение/запись Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Определяет, совместно используется ли презентация несколькими людьми. Чтение/запись Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Указывает общее количество слайдов в документе презентации. Только чтение Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Возвращает или задает тему презентации. Чтение/запись String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Возвращает или задает заголовок презентации. Чтение/запись String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Указывает название каждой части документа. Эти части не являются частями документа, а представляют концептуальные разделы документа. Только чтение string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Общее время редактирования презентации. Чтение/запись TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Указывает общее количество слов в документе. Только чтение Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Очищает и устанавливает значения по умолчанию для всех встроенных свойств. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Удаляет все пользовательские свойства. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Проверяет наличие пользовательского свойства с указанным именем. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Возвращает имя пользовательского свойства по указанному индексу. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Получает именованное булево значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Получает именованное значение DateTime из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Получает именованное значение double из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Получает именованное значение float из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Получает именованное целочисленное значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Получает именованное строковое значение из пользовательских свойств. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Получает массив меток чувствительности из пользовательских свойств документа (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Удаляет пользовательское свойство, связанное с указанным именем. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Устанавливает именованное булево пользовательское свойство. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Устанавливает именованное пользовательское свойство DateTime. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Устанавливает именованное пользовательское свойство double. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Устанавливает именованное пользовательское свойство float. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Устанавливает именованное целочисленное пользовательское свойство. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Устанавливает именованное строковое пользовательское свойство. |

### Смотрите также

* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->