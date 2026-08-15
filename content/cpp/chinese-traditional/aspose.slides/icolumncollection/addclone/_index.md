---
title: AddClone()
second_title: Aspose.Slides for C++ API 參考
description: 建立指定範本列的副本，並將其插入表格的底部。
type: docs
weight: 14
url: /zh-hant/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method


建立指定範本列的副本，並將其插入表格底部。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) 用作範本。 |
| withAttachedColumns | **bool** | True 以同時複製附加於範本列的所有欄。 |

### 返回值

已加入的欄。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IColumn](../../icolumn/)
* 類別 [IColumnCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)