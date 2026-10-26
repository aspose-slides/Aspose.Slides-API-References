---
title: MergeCells()
second_title: Aspose.Slides for C++ API 参考
description: 合并相邻单元格。
type: docs
weight: 261
url: /zh/aspose.slides/itable/mergecells/
---
## ITable::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) 方法

合并相邻的单元格。

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITable::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) 用于合并。 |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) 用于合并。 |
| allowSplitting | **bool** | True 以允许单元格拆分。 |

### 返回值

已合并的单元格。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ICell](../../icell/)
* 类 [ITable](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)