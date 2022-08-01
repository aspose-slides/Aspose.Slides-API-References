---
title: DocumentProperties
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет свойства презентации.
type: docs
weight: 2640
url: /ru/net/aspose.slides/documentproperties/
---
## DocumentProperties class

Представляет свойства презентации.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DocumentProperties](documentproperties)() | Инициализирует новый экземпляр класса[`DocumentProperties`](../documentproperties) . |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Возвращает или задает шаблон приложения. Чтение/записьString . |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Возвращает версию приложения. Только для чтенияString . |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Возвращает или устанавливает автора презентации. Чтение/записьString . |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Возвращает или задает категорию презентации. Чтение/записьString . |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Возвращает или задает комментарии к презентации. Чтение/записьString . |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Возвращает или задает свойство компании. Чтение/записьString . |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Возвращает или устанавливает статус содержимого презентации. Чтение/записьString . |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Возвращает или задает тип содержимого презентации. Чтение/записьString . |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Возвращает количество пользовательских свойств, фактически содержащихся в коллекции. Только для чтенияInt32 . |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Возвращает дату создания презентации. Чтение/записьDateTime . |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Возвращает или задает свойство документа HyperlinkBase. Чтение/записьString . |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Возвращает или устанавливает пользовательское свойство, связанное с указанным именем. Чтение/записьObject . |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Возвращает или задает ключевые слова презентации. Чтение/записьString . |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Возвращает дату последней печати презентации. Чтение/записьDateTime . |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Возвращает или задает имя последнего человека, изменившего презентацию. Чтение/записьString . |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Возвращает дату, когда презентация была изменена в последний раз. Только для чтения в случае Presentation.DocumentProperties (поскольку он будет обновляться внутри во время процесса сохранения объекта IPresentation). Можно изменить с помощью экземпляра DocumentProperties, возвращаемого методом[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) См. пример в[`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties)сводка метода. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Возвращает или задает свойство менеджера. Чтение/записьString . |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Возвращает или задает имя приложения. Чтение/записьString . |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Возвращает или задает предполагаемый формат презентации. Чтение/записьString . |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Возвращает или задает номер версии презентации. Чтение/записьInt32 . |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Определяет, будет ли презентация совместно использоваться несколькими людьми. Чтение/записьBoolean . |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Возвращает или задает тему презентации. Чтение/записьString . |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Возвращает или задает заголовок презентации. Чтение/записьString . |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Общее время редактирования презентации. Чтение/записьTimeSpan . |

## Методы

| Имя | Описание |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Очищает и устанавливает значения по умолчанию для всех встроенных свойств. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Удаляет все пользовательские свойства. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Клонирует текущий объект |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Клонирует текущий объект |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Проверить наличие пользовательского свойства с указанным именем. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Возвращает имя пользовательского свойства по указанному индексу. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Получает именованное логическое значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Получает именованное значение DateTime из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Получает именованное двойное значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Получает именованное значение с плавающей запятой из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Получает именованное целочисленное значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Получает именованное строковое значение из пользовательских свойств. |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Удалить пользовательское свойство, связанное с указанным именем. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Задает именованное логическое пользовательское свойство. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Задает именованное пользовательское свойство DateTime. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Задает именованное двойное пользовательское свойство. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Задает именованное пользовательское свойство с плавающей запятой. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Задает именованное целочисленное пользовательское свойство. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Задает пользовательское свойство именованной строки. |

### Смотрите также

* interface [IDocumentProperties](../idocumentproperties)
* interface [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
