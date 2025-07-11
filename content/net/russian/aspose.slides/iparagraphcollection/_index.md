---
title: IParagraphCollection
second_title: Aspose.Sildes для .NET API Reference
description: Представляет коллекцию параграфов.
type: docs
weight: 6370
url: /ru/aspose.slides/iparagraphcollection/
---

## Интерфейс IParagraphCollection

Представляет коллекцию параграфов.

```csharp
public interface IParagraphCollection : IEnumerable<IParagraph>, ISlideComponent
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIEnumerable](../../aspose.slides/iparagraphcollection/asienumerable) { get; } | Возвращает интерфейс IEnumerable. Только для чтения IEnumerable. |
| [AsISlideComponent](../../aspose.slides/iparagraphcollection/asislidecomponent) { get; } | Позволяет получить основной интерфейс ISlideComponent. Только для чтения [`ISlideComponent`](../islidecomponent). |
| [Count](../../aspose.slides/iparagraphcollection/count) { get; } | Получает количество элементов, фактически содержащихся в коллекции. Только для чтения Int32. |
| [Item](../../aspose.slides/iparagraphcollection/item) { get; } | Получает элемент по указанному индексу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.slides/iparagraphcollection/add#add_1)(IParagraph) | Добавляет параграф в конец коллекции. |
| [Add](../../aspose.slides/iparagraphcollection/add#add)(IParagraphCollection) | Добавляет содержимое ParagraphCollection в конец коллекции. |
| [AddFromHtml](../../aspose.slides/iparagraphcollection/addfromhtml#addfromhtml)(string) | Добавляет текст из указанной строки html в коллекцию. |
| [AddFromHtml](../../aspose.slides/iparagraphcollection/addfromhtml#addfromhtml_1)(string, IExternalResourceResolver, string) | Добавляет текст из указанной строки html в коллекцию. |
| [Clear](../../aspose.slides/iparagraphcollection/clear)() | Удаляет все элементы из коллекции. |
| [ExportToHtml](../../aspose.slides/iparagraphcollection/exporttohtml)(int, int, ITextToHtmlConversionOptions) | Конвертирует указанные параграфы в HTML и возвращает его как объект String. |
| [Insert](../../aspose.slides/iparagraphcollection/insert#insert)(int, IParagraph) | Вставляет параграф в коллекцию по указанному индексу. |
| [Insert](../../aspose.slides/iparagraphcollection/insert#insert_1)(int, IParagraphCollection) | Вставляет содержимое ParagraphCollection в коллекцию по указанному индексу. |
| [Remove](../../aspose.slides/iparagraphcollection/remove)(IParagraph) | Удаляет первое вхождение конкретного параграфа. |
| [RemoveAt](../../aspose.slides/iparagraphcollection/removeat)(int) | Удаляет элемент по указанному индексу коллекции. |

### Также смотри

* интерфейс [IParagraph](../iparagraph)
* интерфейс [ISlideComponent](../islidecomponent)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->