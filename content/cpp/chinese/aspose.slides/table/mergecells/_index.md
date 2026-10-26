---
title: MergeCells()
second_title: Aspose.Slides for C++ API 参考
description: 合并相邻单元格。
type: docs
weight: 274
url: /zh/aspose.slides/table/mergecells/
---
## Table::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) 方法


合并相邻单元格。

```cpp
System::SharedPtr<ICell> Aspose::Slides::Table::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) 合并。 |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) 合并。 |
| allowSplitting | **bool** | True 以允许单元格拆分。 |

### 返回值

合并后的单元格。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ICell](../../icell/)
* 类 [Table](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)