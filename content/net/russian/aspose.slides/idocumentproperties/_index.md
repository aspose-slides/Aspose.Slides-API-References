---
title: IDocumentProperties
second_title: Aspose.Sildes для .NET API Reference
description: Представляет свойства презентации.
type: docs
weight: 5510
url: /ru/aspose.slides/idocumentproperties/
---

## Интерфейс IDocumentProperties

Представляет свойства презентации.

```csharp
public interface IDocumentProperties
```

## Свойства

| Название | Описание |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Возвращает или задает шаблон приложения. Чтение/запись строка. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Возвращает версию приложения. Только для чтения строка. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Возвращает или задает автора презентации. Чтение/запись строка. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Возвращает или задает категорию презентации. Чтение/запись строка. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Возвращает или задает комментарии к презентации. Чтение/запись строка. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Возвращает или задает свойство компании. Чтение/запись строка. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Возвращает или задает статус содержимого презентации. Чтение/запись строка. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Возвращает или задает тип содержимого презентации. Чтение/запись строка. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Возвращает количество пользовательских свойств, фактически содержащихся в коллекции. Только для чтения Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Возвращает дату создания презентации. Значения в UTC. Чтение/запись DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Указывает на групировку частей документа и количество частей в каждой группе. Только для чтения IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Указывает количество скрытых слайдов в документе презентации. Только для чтения Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Возвращает или задает свойство документа HyperlinkBase. Чтение/запись строка. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Указывает, что один или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий этот документ, должен обновить отношения гиперссылок с новыми гиперссылками, указанными в этой части. Чтение/запись логическое. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Возвращает или задает пользовательское свойство, связанное с указанным именем. Чтение/запись объект. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Возвращает или задает ключевые слова презентации. Чтение/запись строка. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Возвращает дату последней печати презентации. Чтение/запись DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Возвращает или задает имя последнего человека, изменившего презентацию. Чтение/запись строка. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Возвращает дату последнего изменения презентации. Значения в UTC. Только для чтения в случае Presentation.DocumentProperties (поскольку он будет обновлен внутренне во время процесса сохранения объекта IPresentation). Может быть изменен через экземпляр DocumentProperties, возвращаемый методом [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Пожалуйста, смотрите пример в сводке метода [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Указывает, являются ли гиперссылки в документе актуальными. Установите этот элемент в **true**, чтобы указать, что гиперссылки обновлены. Установите этот элемент в **false**, чтобы указать, что гиперссылки устарели. Чтение/запись логическое. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Возвращает или задает свойство менеджера. Чтение/запись строка. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Указывает общее количество звуковых или видео клипов, присутствующих в документе. Только для чтения Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Возвращает или задает имя приложения. Чтение/запись строка. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Указывает количество слайдов в презентации, содержащих заметки. Только для чтения Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Указывает общее количество абзацев, найденных в документе, если применимо. Только для чтения Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Возвращает или задает предполагаемый формат презентации. Чтение/запись строка. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Возвращает или задает номер ревизии презентации. Чтение/запись Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Указывает режим отображения миниатюры документа. Установите этот элемент в **true**, чтобы включить масштабирование миниатюры документа к отображению. Установите этот элемент в **false**, чтобы включить обрезку миниатюры документа, чтобы показать только части, которые fit в отображение. Чтение/запись логическое. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Определяет, разделяется ли презентация между несколькими людьми. Чтение/запись логическое. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Указывает общее количество слайдов в документе презентации. Только для чтения Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Возвращает или задает тему презентации. Чтение/запись строка. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Возвращает или задает заголовок презентации. Чтение/запись строка. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Указывает заголовок каждой части документа. Эти части не являются частями документа, а концептуальными представлениями разделов документа. Только для чтения string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Общее время редактирования презентации. Чтение/запись TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Указывает общее количество слов, содержащихся в документе. Только для чтения Int32. |

## Методы

| Название | Описание |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Очищает и устанавливает значения по умолчанию для всех встроенных свойств. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Удаляет все пользовательские свойства. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Проверяет наличие пользовательского свойства с указанным именем. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Возвращает имя пользовательского свойства по указанному индексу. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Получает именованное логическое значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Получает именованное значение DateTime из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Получает именованное значение double из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Получает именованное значение float из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Получает именованное целочисленное значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Получает именованное строковое значение из пользовательских свойств. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Удаляет пользовательское свойство, связанное с указанным именем. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Устанавливает именованное логическое пользовательское свойство. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Устанавливает именованное пользовательское свойство DateTime. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Устанавливает именованное пользовательское свойство double. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Устанавливает именованное пользовательское свойство float. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Устанавливает именованное пользовательское свойство целое число. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Устанавливает именованное пользовательское свойство строка. |

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->