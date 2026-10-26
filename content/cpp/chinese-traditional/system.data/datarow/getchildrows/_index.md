---
title: GetChildRows()
second_title: Aspose.Slides for C++ API 參考
description: 取得透過指定關係被視為子資料列的資料列。
type: docs
weight: 27
url: /zh-hant/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) 方法

取得透過指定關係被視為子資料列的資料列。

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | 用於指定父資料列 - 子資料列關係的關聯物件。 |

### 返回值

[Array](../../../system/array/) 取得的子資料列。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [DataRow](../)
* 類別 [DataRelation](../../datarelation/)
* 命名空間 [System::Data](../../)
* 程式庫 [Aspose.Slides](../../../)