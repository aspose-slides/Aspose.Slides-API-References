---
title: InsertClone()
second_title: Aspose.Slides C++ API 參考
description: 建立指定範本欄位的副本，並將其插入表格中指定的位置。
type: docs
weight: 66
url: /zh-hant/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method


建立指定範本欄位的副本，並將其插入表格中指定的位置。

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 新欄位的索引。 |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) 用作範本。 |
| withAttachedColumns | **bool** | 如果為 true，則同時複製所有附加於範本欄位的欄位。 |

### 回傳值

Inserted columns.

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)