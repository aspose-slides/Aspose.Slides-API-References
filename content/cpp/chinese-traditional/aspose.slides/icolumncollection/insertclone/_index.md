---
title: InsertClone()
second_title: Aspose.Slides C++ API 參考
description: 建立指定範本欄位的副本，並將其插入表格中的指定位置。
type: docs
weight: 27
url: /zh-hant/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method

建立指定範本欄位的副本，並將其插入表格中的指定位置。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 新欄位的索引。 |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) 作為範本使用。 |
| withAttachedColumns | **bool** | 若為 true，則同時複製所有附屬於範本欄位的欄位。 |

### 返回值

已插入的欄位。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IColumn](../../icolumn/)
* 類別 [IColumnCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)