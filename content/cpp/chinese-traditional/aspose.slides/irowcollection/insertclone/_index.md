---
title: InsertClone()
second_title: Aspose.Slides for C++ API 參考手冊
description: 建立指定範本列的副本，並將其插入至表格中的指定位置。
type: docs
weight: 27
url: /zh-hant/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) 方法

建立指定範本列的副本，並將其插入表格中指定的位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 新列的索引。 |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/)，用作範本。 |
| withAttachedRows | **bool** | 若為 true，則同時複製所有附加於範本列的列。 |

### 回傳值

已插入的列。

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IRow](../../irow/)
* 類別 [IRowCollection](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)