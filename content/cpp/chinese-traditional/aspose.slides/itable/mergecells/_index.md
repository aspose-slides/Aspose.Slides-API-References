---
title: MergeCells()
second_title: Aspose.Slides for C++ API 參考
description: 合併相鄰儲存格。
type: docs
weight: 261
url: /zh-hant/aspose.slides/itable/mergecells/
---
## ITable::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) method


合併相鄰的儲存格。

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITable::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting)=0
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) 用於合併。 |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) 用於合併。 |
| allowSplitting | **bool** | True 以允許儲存格分割。 |

### 返回值

已合併的儲存格。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICell](../../icell/)
* Class [ITable](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)