---
title: MergeCells()
second_title: Aspose.Slides for C++ API Reference
description: Merges neighbour cells.
type: docs
weight: 261
url: /cpp/aspose.slides/itable/mergecells/
---
## ITable::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) method


Merges neighbour cells.

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITable::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting)=0
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
* Class [ITable](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)