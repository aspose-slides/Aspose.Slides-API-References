---
title: ColumnCollection
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет набор столбцов в таблице.
type: docs
weight: 2450
url: /ru/net/aspose.slides/columncollection/
---
## ColumnCollection class

Представляет набор столбцов в таблице.

```csharp
public sealed class ColumnCollection : DomObject<RowCollection>, IColumnCollection
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.slides/columncollection/count) { get; } | Возвращает количество столбцов в коллекции. Только для чтенияInt32. |
| [IsSynchronized](../../aspose.slides/columncollection/issynchronized) { get; } | Возвращает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). Только чтениеBoolean. |
| [Item](../../aspose.slides/columncollection/item) { get; } | Возвращает столбец по указанному индексу. Только чтение[`Column`](../column). |
| [SyncRoot](../../aspose.slides/columncollection/syncroot) { get; } | Возвращает корень синхронизации. Только для чтенияObject. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddClone](../../aspose.slides/columncollection/addclone)(IColumn, bool) | Создает копию указанной строки шаблона и вставляет ее внизу таблицы. |
| [CopyTo](../../aspose.slides/columncollection/copyto)(Array, int) | Копирует все элементы из коллекции в указанный массив. |
| [GetEnumerator](../../aspose.slides/columncollection/getenumerator)() | Возвращает перечислитель, который перебирает коллекцию. |
| [InsertClone](../../aspose.slides/columncollection/insertclone)(int, IColumn, bool) | Создает копию указанного столбца шаблона и вставляет его в указанную позицию в таблице. |
| [RemoveAt](../../aspose.slides/columncollection/removeat)(int, bool) | Удаляет столбец в указанной позиции из таблицы. |

### Смотрите также

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [RowCollection](../rowcollection)
* interface [IColumnCollection](../icolumncollection)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->