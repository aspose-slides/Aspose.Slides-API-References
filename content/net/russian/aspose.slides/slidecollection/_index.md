---
title: SlideCollection
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет собой коллекцию слайдов.
type: docs
weight: 9660
url: /ru/aspose.slides/slidecollection/
---

## Класс SlideCollection

Представляет собой коллекцию слайдов.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Свойства

| Название | Описание |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Получает количество элементов, фактически содержащихся в коллекции. Только для чтения Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потоко-безопасно). Только для чтения Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Возвращает корень синхронизации. Только для чтения Object. |

## Методы

| Название | Описание |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Добавляет копию указанного слайда в конец указанного раздела. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Добавляет копию указанного исходного слайда в конец коллекции. Подходящий макет будет автоматически выбран из указанного мастера (подходящий макет - это макет с тем же типом или именем, что и макет исходного слайда). Если подходящего макета нет, макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выдано исключение PptxEditException (если allowCloneMissingLayout равно false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Добавляет новый пустой слайд в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Создает слайды из HTML текста и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Создает слайды из документа PDF и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Создает слайды из документа PDF и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Создает слайды из документа PDF и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Создает слайды из документа PDF и добавляет их в конец коллекции с учетом параметров импорта PDF. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Копирует все элементы из коллекции в указанный массив. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Возвращает перечислитель, который итеративно проходит через коллекцию. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Возвращает индекс указанного слайда в коллекции. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Вставляет копию указанного исходного слайда в указанную позицию коллекции. Подходящий макет будет автоматически выбран из указанного мастера (подходящий макет - это макет с тем же типом или именем, что и макет исходного слайда). Если подходящего макета нет, макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выдано исключение PptxEditException (если allowCloneMissingLayout равно false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Создает слайды из HTML текста и вставляет их в коллекцию в указанной позиции. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Удаляет первое вхождение конкретного объекта из коллекции. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Удаляет элемент по указанному индексу из коллекции. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Перемещает слайд из коллекции в указанную позицию. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Перемещает слайды из коллекции в указанную позицию. Слайды будут размещены, начиная с индекса, в порядке их появления в списке. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Создает и возвращает массив со всеми слайдами в нем. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Создает и возвращает массив со всеми слайдами из указанного диапазона в нем. Индекс первого слайда для добавления. Количество слайдов для добавления. |

### См. Также

* класс [DomObject&lt;TParent&gt;](../domobject-1)
* класс [Presentation](../presentation)
* интерфейс [ISlideCollection](../islidecollection)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->