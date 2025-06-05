---
title: DocumentProperties
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет свойства презентации.
type: docs
weight: 2700
url: /ru/aspose.slides/documentproperties/
---

## DocumentProperties class

Представляет свойства презентации.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DocumentProperties](documentproperties)() | Инициализирует новый экземпляр класса [`DocumentProperties`](../documentproperties). |

## Свойства

| Имя | Описание |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Возвращает или задает шаблон приложения. Чтение/запись String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Возвращает версию приложения. Только для чтения String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Возвращает или задает автора презентации. Чтение/запись String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Возвращает или задает категорию презентации. Чтение/запись String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Возвращает или задает комментарии к презентации. Чтение/запись String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Возвращает или задает свойство компании. Чтение/запись String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Возвращает или задает статус содержания презентации. Чтение/запись String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Возвращает или задает тип содержания презентации. Чтение/запись String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Возвращает количество настраиваемых свойств, фактически содержащихся в коллекции. Только для чтения Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Возвращает дату создания презентации. Значения в UTC. Чтение/запись DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Указывает группировку частей документа и количество частей в каждой группе. Только для чтения IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Возвращает количество скрытых слайдов в документе презентации. Только для чтения Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Возвращает или задает свойство документа HyperlinkBase. Чтение/запись String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий этот документ, должен обновить отношения гиперссылок с новыми гиперссылками, указанными в этой части. Чтение/запись Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Возвращает или задает настраиваемое свойство, связанное с указанным именем. Чтение/запись Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Возвращает или задает ключевые слова презентации. Чтение/запись String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Возвращает дату, когда презентация печаталась в последний раз. Чтение/запись DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Возвращает или задает имя последнего лица, изменившего презентацию. Чтение/запись String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Возвращает дату последнего изменения презентации. Значения в UTC. Только для чтения в случае Presentation.DocumentProperties (поскольку он будет обновлен внутренне в процессе сохранения объекта IPresentation). Может быть изменен через экземпляр DocumentProperties, возвращаемый методом [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) Пожалуйста, смотрите пример в сводке метода [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Указывает, являются ли гиперссылки в документе актуальными. Установите этот элемент в **true**, чтобы указать, что гиперссылки обновлены. Установите этот элемент в **false**, чтобы указать, что гиперссылки устарели. Чтение/запись Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Возвращает или задает свойство менеджера. Чтение/запись String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Возвращает общее количество звуковых или видеоклипов, присутствующих в документе. Только для чтения Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Возвращает или задает имя приложения. Чтение/запись String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Возвращает количество слайдов в презентации, содержащих заметки. Только для чтения Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Возвращает общее количество абзацев, найденных в документе, если применимо. Только для чтения Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Возвращает или задает предполагаемый формат презентации. Чтение/запись String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Возвращает или задает номер ревизии презентации. Чтение/запись Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Указывает режим отображения миниатюры документа. Установите этот элемент в **true**, чтобы включить масштабирование миниатюры документа для отображения. Установите этот элемент в **false**, чтобы включить обрезку миниатюры документа, чтобы показать только те части, которые соответствуют дисплею. Чтение/запись Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Определяет, является ли презентация общей между несколькими людьми. Чтение/запись Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Возвращает общее количество слайдов в документе презентации. Только для чтения Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Возвращает или задает тему презентации. Чтение/запись String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Возвращает или задает заголовок презентации. Чтение/запись String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Указывает заголовок каждой части документа. Эти части не являются частями документа, а концептуальными представлениями разделов документа. Только для чтения string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Общее время редактирования презентации. Чтение/запись TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Возвращает общее количество слов, содержащихся в документе. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Очищает и устанавливает значения по умолчанию для всех встроенных свойств. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Удаляет все настраиваемые свойства. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Клонирует текущий объект |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Клонирует текущий объект |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Проверяет наличие настраиваемого свойства с указанным именем. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Возвращает имя настраиваемого свойства по указанному индексу. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Получает именованное логическое значение из настраиваемых свойств. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Получает именованное значение DateTime из настраиваемых свойств. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Получает именованное значение double из настраиваемых свойств. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Получает именованное значение float из настраиваемых свойств. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Получает именованное целочисленное значение из настраиваемых свойств. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Получает именованное строковое значение из настраиваемых свойств. |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Удаляет настраиваемое свойство, связанное с указанным именем. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Устанавливает именованное логическое настраиваемое свойство. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Устанавливает именованное значение DateTime для настраиваемого свойства. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Устанавливает именованное значение double для настраиваемого свойства. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Устанавливает именованное значение float для настраиваемого свойства. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Устанавливает именованное целочисленное значение для настраиваемого свойства. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Устанавливает именованное строковое значение для настраиваемого свойства. |

### Примеры

Следующий пример демонстрирует, как получить доступ к встроенным свойствам презентации PowerPoint.

```csharp
[C#]
// Создать экземпляр класса Presentation, который представляет презентацию
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Создать ссылку на объект IDocumentProperties, связанный с Presentation
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Вывести встроенные свойства
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

Следующий пример демонстрирует, как изменить встроенные свойства презентации PowerPoint.

```csharp
[C#]
// Создать экземпляр класса Presentation, который представляет презентацию
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Создать ссылку на объект IDocumentProperties, связанный с Presentation
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Установить встроенные свойства
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Изменение свойств презентации";
	documentProperties.Subject = "Тематика Aspose";
	// Сохраните вашу презентацию в файл
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [IDocumentProperties](../idocumentproperties)
* интерфейс [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->