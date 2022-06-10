---
title: IDocumentProperties
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет свойства презентации.
type: docs
weight: 5210
url: /ru/net/aspose.slides/idocumentproperties/
---
## IDocumentProperties interface

Представляет свойства презентации.

```csharp
public interface IDocumentProperties
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Возвращает или задает шаблон приложения. Чтение/записьString. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Возвращает версию приложения. Только чтениеString. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Возвращает или устанавливает автора презентации. Чтение/записьString. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Возвращает или задает категорию презентации. Чтение/записьString. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Возвращает или задает комментарии презентации. Чтение/записьString. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Возвращает или задает свойство компании. Чтение/записьString. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Возвращает или устанавливает статус содержимого презентации. Чтение/записьString. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Возвращает или задает тип содержимого презентации. Чтение/записьString. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Возвращает количество пользовательских свойств, фактически содержащихся в коллекции. Только для чтенияInt32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Возвращает дату создания презентации. Чтение/записьDateTime. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Возвращает или задает свойство документа HyperlinkBase. Чтение/записьString. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Возвращает или задает пользовательское свойство, связанное с указанным именем. Чтение/записьObject. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Возвращает или устанавливает ключевые слова презентации. Чтение/записьString. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Возвращает дату последней печати презентации. Чтение/записьDateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Возвращает или задает имя последнего человека, изменившего презентацию. Чтение/записьString. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Возвращает дату последнего изменения презентации. Только для чтения в случае Presentation.DocumentProperties (поскольку он будет обновляться внутри во время процесса сохранения объекта IPresentation). Можно изменить с помощью экземпляра DocumentProperties, возвращаемого методом[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) См. пример в[`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties)сводка методов. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Возвращает или устанавливает свойство менеджера. Чтение/записьString. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Возвращает или задает имя приложения. Чтение/записьString. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Возвращает или задает предполагаемый формат презентации. Чтение/записьString. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Возвращает или задает номер версии презентации. Чтение/записьInt32. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Определяет, будет ли презентация совместно использоваться несколькими людьми. Чтение/записьBoolean. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Возвращает или задает тему презентации. Чтение/записьString. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Возвращает или задает заголовок презентации. Чтение/записьString. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Общее время редактирования презентации. Чтение/записьTimeSpan. |

## Методы

| Имя | Описание |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Очищает и устанавливает значения по умолчанию для всех встроенных свойств. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Удаляет все пользовательские свойства. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Проверить наличие пользовательского свойства с указанным именем. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Возвращает имя пользовательского свойства по указанному индексу. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Получает именованное логическое значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Получает именованное значение DateTime из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Получает именованное двойное значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Получает именованное значение с плавающей запятой из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Получает именованное целочисленное значение из пользовательских свойств. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Получает именованное строковое значение из пользовательских свойств. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Удалить пользовательское свойство, связанное с указанным именем. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Задает именованное логическое пользовательское свойство. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Задает именованное пользовательское свойство DateTime. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Устанавливает именованное двойное пользовательское свойство. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Устанавливает именованное пользовательское свойство с плавающей запятой. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Устанавливает именованное целочисленное пользовательское свойство. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Задает пользовательское свойство именованной строки. |

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
