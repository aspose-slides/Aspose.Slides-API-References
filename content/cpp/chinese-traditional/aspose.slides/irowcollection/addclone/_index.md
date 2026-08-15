---
title: AddClone()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立指定範本列的副本，並將其插入表格的底部。
type: docs
weight: 14
url: /zh-hant/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) 方法

建立指定範本列的副本，並將其插入表格的底部。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) 用作範本。 |
| withAttachedRows | **bool** | True 表示同時複製所有附加在範本列上的列。 |

### 傳回值

已新增的列。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IRow](../../irow/)
* 類別 [IRowCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)