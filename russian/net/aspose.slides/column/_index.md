---
title: Column
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет столбец в таблице.
type: docs
weight: 2440
url: /ru/net/aspose.slides/column/
---
## Column class

Представляет столбец в таблице.

```csharp
public sealed class Column : CellCollection, IColumn
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ColumnFormat](../../aspose.slides/column/columnformat) { get; } | Возвращает объект ColumnFormat, содержащий свойства форматирования для этого столбца. Только для чтения[`IColumnFormat`](../icolumnformat). |
| [Count](../../aspose.slides/cellcollection/count) { get; } | Возвращает количество ячеек в коллекции. Только для чтенияInt32. |
| [IsSynchronized](../../aspose.slides/cellcollection/issynchronized) { get; } | Возвращает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). Только чтениеBoolean. |
| [Item](../../aspose.slides/cellcollection/item) { get; } | Возвращает ячейку по ее положению. Только для чтения[`Cell`](../cell). |
| [Presentation](../../aspose.slides/cellcollection/presentation) { get; } | Возвращает родительское представление CellCollection. Только чтение[`IPresentation`](../ipresentation). |
| [Slide](../../aspose.slides/cellcollection/slide) { get; } | Возвращает родительский слайд CellCollection. Только для чтения[`IBaseSlide`](../ibaseslide). |
| [SyncRoot](../../aspose.slides/cellcollection/syncroot) { get; } | Возвращает корень синхронизации. Только для чтенияObject. |
| [Width](../../aspose.slides/column/width) { get; set; } | Возвращает или задает ширину столбца. Чтение/записьDouble. |

## Методы

| Имя | Описание |
| --- | --- |
| [CopyTo](../../aspose.slides/cellcollection/copyto)(Array, int) | Копирует все элементы из коллекции в указанный массив. |
| [GetEnumerator](../../aspose.slides/cellcollection/getenumerator)() | Возвращает перечислитель, который перебирает коллекцию. |
| [SetTextFormat](../../aspose.slides/column/settextformat#settextformat)(IParagraphFormat) | Устанавливает определенные свойства формата абзаца для всех абзацев ячеек столбца. |
| [SetTextFormat](../../aspose.slides/column/settextformat#settextformat_1)(IPortionFormat) | Устанавливает определенные свойства формата части для всех частей ячеек столбца. |
| [SetTextFormat](../../aspose.slides/column/settextformat#settextformat_2)(ITextFrameFormat) | Устанавливает определенные свойства формата текстового фрейма для всех текстовых фреймов ячеек столбца. |

### Смотрите также

* class [CellCollection](../cellcollection)
* interface [IColumn](../icolumn)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->