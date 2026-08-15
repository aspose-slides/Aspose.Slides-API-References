---
title: InsertTable()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新表格，並將其插入至指定索引的 shape collection 中。
type: docs
weight: 482
url: /zh-hant/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) 方法

建立一個新表格，並將其插入至指定索引的 shape collection 中。

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 插入表格時的零基索引。 |
| x | **float** | 表格的 x 座標，單位為點。 |
| y | **float** | 表格的 y 座標，單位為點。 |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 表示表格各欄位寬度的 double 陣列，單位為點。 |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 表示表格各列高度的 double 陣列，單位為點。 |

### 回傳值

新建立的 [ITable](../../itable/)。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [ITable](../../itable/)
* 類別 [ShapeCollection](../)
* 名稱空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)