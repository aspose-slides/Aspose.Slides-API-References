---
title: ISlideCollection
second_title: Aspose.Sildes для .NET API Reference
description: Представляет коллекцию слайдов.
type: docs
weight: 7050
url: /ru/aspose.slides/islidecollection/
---
## ISlideCollection интерфейс

Представляет коллекцию слайдов.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Возвращает элемент по указанному индексу. Только для чтения [`ISlide`](../islide). |

## Методы

| Имя | Описание |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Добавляет копию указанного слайда в конец указанного раздела. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Добавляет копию указанного исходного слайда в конец коллекции. Соответствующий шаблон будет выбран автоматически из указанного мастера (соответствующий шаблон — это шаблон с тем же Type или Name, что и шаблон исходного слайда). Если подходящего шаблона нет, то шаблон исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Добавляет новый пустой слайд в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции с учётом параметров импорта PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Возвращает индекс указанного слайда в коллекции. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Вставляет копию указанного исходного слайда в указанную позицию коллекции. Соответствующий шаблон будет выбран автоматически из указанного мастера (соответствующий шаблон — это шаблон с тем же Type или Name, что и шаблон исходного слайда). Если подходящего шаблона нет, то шаблон исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Удаляет первое вхождение указанного объекта из коллекции. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Удаляет элемент по указанному индексу в коллекции. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Перемещает слайд в коллекции в указанную позицию. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Перемещает слайды в коллекции в указанную позицию. Слайды будут размещены, начиная с индекса, в порядке их появления в списке. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Создаёт и возвращает массив со всеми слайдами. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Создаёт и возвращает массив со всеми слайдами из указанного диапазона. |

### См. также

* интерфейс [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* интерфейс [ISlide](../islide)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->