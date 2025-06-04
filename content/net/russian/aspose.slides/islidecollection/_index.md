---
title: ISlideCollection
second_title: Aspose.Sildes for .NET API Reference
description: Представляет коллекцию слайдов.
type: docs
weight: 6830
url: /ru/aspose.slides/islidecollection/
---

## Интерфейс ISlideCollection

Представляет коллекцию слайдов.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Свойства

| Название | Описание |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения [`ISlide`](../islide). |

## Методы

| Название | Описание |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Добавляет копию указанного слайда в конец указанного раздела. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Добавляет копию указанного исходного слайда в конец коллекции. Подходящий макет будет автоматически выбран из указанного мастера (подходящий макет - это макет с тем же Типом или Именем, что и макет исходного слайда). Если подходящего макета нет, макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Добавляет новый пустой слайд в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Создает слайды из PDF документа и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Создает слайды из PDF документа и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Создает слайды из PDF документа и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Создает слайды из PDF документа и добавляет их в конец коллекции с учетом параметров импорта pdf. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Возвращает индекс указанного слайда в коллекции. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Вставляет копию указанного слайда в заданную позицию коллекции. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Вставляет копию указанного слайда в заданную позицию коллекции. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Вставляет копию указанного исходного слайда в заданную позицию коллекции. Подходящий макет будет автоматически выбран из указанного мастера (подходящий макет - это макет с тем же Типом или Именем, что и макет исходного слайда). Если подходящего макета нет, макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Вставляет копию указанного слайда в заданную позицию коллекции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Удаляет первое вхождение конкретного объекта из коллекции. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Удаляет элемент по указанному индексу из коллекции. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Перемещает слайд из коллекции в указанную позицию. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Перемещает слайды из коллекции в указанную позицию. Слайды будут помещены, начиная с индекса, в порядке их появления в списке. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Создает и возвращает массив со всеми слайдами в нем. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Создает и возвращает массив со всеми слайдами из указанного диапазона в нем. |

### Смотрите также

* интерфейс [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* интерфейс [ISlide](../islide)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->