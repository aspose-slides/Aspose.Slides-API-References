---
title: SlideCollection
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет коллекцию слайдов.
type: docs
weight: 9190
url: /ru/net/aspose.slides/slidecollection/
---
## SlideCollection class

Представляет коллекцию слайдов.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Получает количество элементов, фактически содержащихся в коллекции. Только для чтенияInt32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Возвращает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). Только чтениеBoolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения[`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Возвращает корень синхронизации. Только для чтенияObject. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Добавляет копию указанного слайда в конец коллекции. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Добавляет копию указанного слайда в конец указанного раздела. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Добавляет копию указанного исходного слайда в конец коллекции. Соответствующий макет будет выбран автоматически из указанного мастера (подходящим макетом является макет с тем же типом или именем, что и макета исходного слайда). ). Если подходящего макета нет, то макет исходного слайда будет клонирован (если значение allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout является ложным). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Добавляет новый пустой слайд в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Создает слайды из текста HTML и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Создает слайды из документа PDF и добавляет их в конец коллекции. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(string) | Создает слайды из документа PDF и добавляет их в конец коллекции. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Копирует все элементы из коллекции в указанный массив. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Возвращает перечислитель, который перебирает коллекцию. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Возвращает индекс указанного слайда в коллекции. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Вставляет копию указанного исходного слайда в указанную позицию коллекции. Соответствующий макет будет выбран автоматически из указанного мастера (подходящим макетом является макет с тем же типом или именем, что и макета исходного слайда). ). Если подходящего макета нет, то макет исходного слайда будет клонирован (если значение allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout является ложным). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, string) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, TextReader) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, string, IExternalResourceResolver, string) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, TextReader, IExternalResourceResolver, string) | Создает слайды из текста HTML и вставляет их в коллекцию в указанной позиции. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Удаляет первое вхождение определенного объекта из коллекции. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Удаляет элемент по указанному индексу коллекции. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Перемещает слайд из коллекции в указанную позицию. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Перемещает слайды из коллекции в указанную позицию. Слайды будут располагаться, начиная с индекса, в порядке их появления в списке. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Создает и возвращает массив со всеми слайдами в нем. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Создает и возвращает массив со всеми слайдами из указанного диапазона в нем.  Индекс первого добавляемого слайда. Количество слайдов для добавления. |

### Смотрите также

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [ISlideCollection](../islidecollection)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
