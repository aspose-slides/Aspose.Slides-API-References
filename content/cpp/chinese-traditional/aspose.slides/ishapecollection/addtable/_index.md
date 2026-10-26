---
title: AddTable()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新表格，並將其加入形狀集合的末端。
type: docs
weight: 430
url: /zh-hant/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) 方法

建立一個新表格，並將其加入形狀集合的末端。

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 表格的 x 座標，單位為點。 |
| y | **float** | 表格的 y 座標，單位為點。 |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 一個 double 陣列，表示表格列的寬度，單位為點。 |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 一個 double 陣列，表示表格行的高度，單位為點。 |

### 回傳值

新建立的 [ITable](../../itable/)。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [ITable](../../itable/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)