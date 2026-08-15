---
title: MergeCells()
second_title: Aspose.Slides C++ API 參考
description: 合併相鄰儲存格。
type: docs
weight: 274
url: /zh-hant/aspose.slides/table/mergecells/
---
## Table::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) 方法

合併相鄰儲存格。

```cpp
System::SharedPtr<ICell> Aspose::Slides::Table::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) 以合併。 |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) 以合併。 |
| allowSplitting | **bool** | True 允許儲存格拆分。 |

### 返回值

已合併的儲存格。

## 參見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ICell](../../icell/)
* 類別 [Table](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)