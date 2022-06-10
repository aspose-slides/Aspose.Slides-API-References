---
title: ISlideCollection
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет коллекцию слайдов.
type: docs
weight: 6470
url: /ru/net/aspose.slides/islidecollection/
---
## ISlideCollection interface

Представляет коллекцию слайдов.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения[`ISlide`](../islide). |

## Методы

| Имя | Описание |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Добавляет копию указанного слайда в конец указанного раздела. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Добавляет копию указанного исходного слайда в конец коллекции. Соответствующий макет будет выбран автоматически из указанного мастера (подходящим макетом является макет с тем же типом или именем, что и макета исходного слайда). ). Если подходящего макета нет, то макет исходного слайда будет клонирован (если значение allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout является ложным). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Добавляет новый пустой слайд в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Создает слайды из документа PDF и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(string) | Создает слайды из документа PDF и добавляет их в конец коллекции. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Возвращает индекс указанного слайда в коллекции. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Вставляет копию указанного исходного слайда в указанную позицию коллекции. Соответствующий макет будет выбран автоматически из указанного мастера (подходящим макетом является макет с тем же типом или именем, что и макета исходного слайда). ). Если подходящего макета нет, то макет исходного слайда будет клонирован (если значение allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout является ложным). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, string) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, TextReader) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, string, IExternalResourceResolver, string) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, TextReader, IExternalResourceResolver, string) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Удаляет первое вхождение определенного объекта из коллекции. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Удаляет элемент по указанному индексу коллекции. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Перемещает слайд из коллекции в указанную позицию. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Перемещает слайды из коллекции в указанную позицию. Слайды будут располагаться, начиная с индекса, в порядке их появления в списке. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Создает и возвращает массив со всеми слайдами в нем. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Создает и возвращает массив со всеми слайдами из указанного диапазона в нем. |

### Смотрите также

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [ISlide](../islide)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
