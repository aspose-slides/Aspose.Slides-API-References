---
title: InsertTable()
second_title: Aspose.Slides for C++ API 參考
description: 在指定的索引處建立新表格，並將其插入形狀集合中。
type: docs
weight: 443
url: /zh-hant/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) 方法

建立一個新表格，並將其插入至指定索引的形狀集合中。

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 插入表格的零基索引。 |
| x | **float** | 表格的 x 座標，以點為單位。 |
| y | **float** | 表格的 y 座標，以點為單位。 |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 一個 double 陣列，表示表格\\u2019s 欄位的寬度，以點為單位。 |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 一個 double 陣列，表示表格\\u2019s 行的高度，以點為單位。 |

### 回傳值

新建立的 [ITable](../../itable/)。

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [ITable](../../itable/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)