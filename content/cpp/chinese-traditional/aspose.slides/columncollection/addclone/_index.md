---
title: AddClone()
second_title: Aspose.Slides C++ API 參考
description: 建立指定範本列的副本，並將其插入表格的底部。
type: docs
weight: 53
url: /zh-hant/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) 方法


建立指定範本列的副本，並將其插入表格的底部。

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) 用作範本。 |
| withAttachedColumns | **bool** | True 以同時複製所有附加於範本列的欄位。 |

### 傳回值

已加入的欄位。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IColumn](../../icolumn/)
* 類別 [ColumnCollection](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)