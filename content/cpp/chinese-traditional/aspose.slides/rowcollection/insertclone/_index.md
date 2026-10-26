---
title: InsertClone()
second_title: Aspose.Slides C++ API 參考
description: 建立指定範本列的副本，並將其插入表格中指定的位置。
type: docs
weight: 66
url: /zh-hant/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) 方法

建立指定範本列的副本，並將其插入表格中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 新列的索引。 |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) 用作範本。 |
| withAttachedRows | **bool** | True 表示同時複製所有附加於範本列的列。 |

### 回傳值

已插入的列。

## 另請參閱

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IRow](../../irow/)
* 類別 [RowCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)