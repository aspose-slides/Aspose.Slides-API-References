---
title: MergeCells()
second_title: Справочник API Aspose.Slides для C++
description: Объединяет соседние ячейки.
type: docs
weight: 274
url: /ru/aspose.slides/table/mergecells/
---
## Table::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) method


Объединяет соседние ячейки.

```cpp
System::SharedPtr<ICell> Aspose::Slides::Table::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) для объединения. |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) для объединения. |
| allowSplitting | **bool** | True, чтобы разрешить разбиение ячеек. |

### Возвращаемое значение

Объединённая ячейка.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ICell](../../icell/)
* Класс [Table](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)