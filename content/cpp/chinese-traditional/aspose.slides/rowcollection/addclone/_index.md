---
title: AddClone()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立指定範本列的副本，並將其插入表格的底部。
type: docs
weight: 53
url: /zh-hant/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) 方法

建立指定範本列的副本，並將其插入表格的底部。

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) 用作範本。 |
| withAttachedRows | **bool** | True 會同時複製所有附加於範本列的行。 |

### 回傳值

已新增的列。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IRow](../../irow/)
* 類別 [RowCollection](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)