---
title: SlideCollection
second_title: Aspose.Sildes для .NET справочник API
description: Представляет коллекцию слайдов.
type: docs
weight: 9970
url: /ru/aspose.slides/slidecollection/
---
## SlideCollection класс

Представляет коллекцию слайдов.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Возвращает количество элементов, фактически содержащихся в коллекции. Только для чтения Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Возвращает элемент по указанному индексу. Только для чтения [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Возвращает корень синхронизации. Только для чтения Object. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Добавляет копию указанного слайда в конец указанного раздела. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Добавляет копию указанного исходного слайда в конец коллекции. Подходящий макет будет выбран автоматически из указанного мастер-макета (подходящий макет — это макет с тем же типом или именем, что и макет исходного слайда). Если подходящий макет отсутствует, макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Добавляет новый пустой слайд в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции с учётом параметров импорта PDF. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Копирует все элементы из коллекции в указанный массив. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Возвращает перечислитель, который перебирает элементы коллекции. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Возвращает индекс указанного слайда в коллекции. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Вставляет копию указанного исходного слайда в указанную позицию коллекции. Подходящий макет будет выбран автоматически из указанного мастер-макета (подходящий макет — это макет с тем же типом или именем, что и макет исходного слайда). Если подходящий макет отсутствует, макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Удаляет первое вхождение указанного объекта из коллекции. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Удаляет элемент по указанному индексу из коллекции. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Перемещает слайд в коллекции в указанную позицию. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Перемещает слайды из коллекции в указанную позицию. Слайды будут размещены, начиная с индекса, в порядке их появления в списке. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Создаёт и возвращает массив, содержащий все слайды. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Создаёт и возвращает массив со всеми слайдами из указанного диапазона. Индекс первого добавляемого слайда. Количество слайдов для добавления. |

### См. также

* класс [DomObject&lt;TParent&gt;](../domobject-1)
* класс [Presentation](../presentation)
* интерфейс [ISlideCollection](../islidecollection)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->