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

| Имя | Описание |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Возвращает или устанавливает шаблон приложения. Чтение/запись Строка. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Возвращает версию приложения. Только для чтения Строка. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Возвращает или устанавливает автора презентации. Чтение/запись Строка. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Возвращает или устанавливает категорию презентации. Чтение/запись Строка. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Возвращает или устанавливает комментарии к презентации. Чтение/запись Строка. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Возвращает или устанавливает свойство компании. Чтение/запись Строка. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Возвращает или устанавливает статус содержимого презентации. Чтение/запись Строка. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Возвращает или устанавливает тип контента презентации. Чтение/запись Строка. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Возвращает количество настраиваемых свойств, фактически содержащихся в коллекции. Только для чтения Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Возвращает дату создания презентации. Значения в UTC. Чтение/запись DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Указывает на группировку частей документа и количество частей в каждой группе. Только для чтения IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Указывает количество скрытых слайдов в документе презентации. Только для чтения Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Возвращает или устанавливает документ-свойство HyperlinkBase. Чтение/запись Строка. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Указывает, что один или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий этот документ, должен обновить отношения гиперссылок с новыми гиперссылками, указанными в этой части. Чтение/запись Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Возвращает или устанавливает настраиваемое свойство, связанное с указанным именем. Чтение/запись Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Возвращает или устанавливает ключевые слова презентации. Чтение/запись Строка. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Возвращает дату, когда презентация была последний раз напечатана. Чтение/запись DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Возвращает или устанавливает имя последнего человека, который изменил презентацию. Чтение/запись Строка. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Возвращает дату, когда презентация была последний раз изменена. Значения в UTC. Только для чтения в случае Presentation.DocumentProperties (поскольку она будет обновляться внутренне во время процесса сохранения объекта IPresentation). Может быть изменено через экземпляр DocumentProperties, возвращаемый методом [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Пожалуйста, смотрите пример в сводке метода [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Указывает, являются ли гиперссылки в документе актуальными. Установите этот элемент в **true**, чтобы указать, что гиперссылки обновлены. Установите этот элемент в **false**, чтобы указать, что гиперссылки устарели. Чтение/запись Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Возвращает или устанавливает свойство менеджера. Чтение/запись Строка. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Указывает общее количество аудио или видеофрагментов, присутствующих в документе. Только для чтения Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Возвращает или устанавливает имя приложения. Чтение/запись Строка. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Указывает количество слайдов в презентации, содержащих заметки. Только для чтения Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Указывает общее количество абзацев, обнаруженных в документе, если это применимо. Только для чтения Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Возвращает или устанавливает предполагаемый формат презентации. Чтение/запись Строка. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Возвращает или устанавливает номер ревизии презентации. Чтение/запись Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Указывает режим отображения миниатюры документа. Установите этот элемент в **true**, чтобы включить масштабирование миниатюры документа для отображения. Установите этот элемент в **false**, чтобы включить обрезку миниатюры документа, чтобы показывать только области, которые подходят для отображения. Чтение/запись Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Определяет, разделяется ли презентация между несколькими людьми. Чтение/запись Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Указывает общее количество слайдов в документе презентации. Только для чтения Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Возвращает или устанавливает тему презентации. Чтение/запись Строка. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Возвращает или устанавливает заголовок презентации. Чтение/запись Строка. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Указывает заголовок каждой части документа. Эти части не являются частями документа, а концептуальными представлениями разделов документа. Только для чтения string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Общее время редактирования презентации. Чтение/запись TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Указывает общее количество слов, содержащихся в документе. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Очищает и устанавливает значения по умолчанию для всех встроенных свойств. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Удаляет все настраиваемые свойства. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Проверяет наличие настраиваемого свойства с заданным именем. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Возвращает имя настраиваемого свойства по указанному индексу. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Получает именованное булевское значение из настраиваемых свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Получает именованное значение DateTime из настраиваемых свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Получает именованное значение double из настраиваемых свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Получает именованное значение float из настраиваемых свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Получает именованное целочисленное значение из настраиваемых свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Получает именованное строковое значение из настраиваемых свойств. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Удаляет настраиваемое свойство, связанное с заданным именем. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Устанавливает именованное булевское настраиваемое свойство. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Устанавливает именованное настраиваемое свойство DateTime. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Устанавливает именованное настраиваемое свойство double. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Устанавливает именованное настраиваемое свойство float. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Устанавливает именованное настраиваемое свойство integer. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Устанавливает именованное настраиваемое свойство string. |

### См. также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->