---
title: MergeCells()
second_title: Aspose.Slides for C++ API Reference
description: Merges neighbour cells.
type: docs
weight: 274
url: /aspose.slides/table/mergecells/
---
## Table::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) method


Merges neighbour cells.

```cpp
System::SharedPtr<ICell> Aspose::Slides::Table::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) to merge. |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) to merge. |
| allowSplitting | **bool** | True to allow cells splitting. |

### Return Value

Merged cell.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICell](../../icell/)
* Class [Table](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)