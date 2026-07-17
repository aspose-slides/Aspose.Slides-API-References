---
title: InsertTable()
second_title: Aspose.Slides C++ API 参考
description: 在指定索引处创建一个新表格并将其插入到形状集合中。
type: docs
weight: 482
url: /zh/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) 方法

创建一个新表格并将其插入到指定索引的形状集合中。

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入表格的基于零的索引。 |
| x | **float** | 表格的 x 坐标，单位为点。 |
| y | **float** | 表格的 y 坐标，单位为点。 |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 表示表格列宽的 double 数组，单位为点。 |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 表示表格行高的 double 数组，单位为点。 |

### 返回值

新创建的 [ITable](../../itable/)。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [ITable](../../itable/)
* 类 [ShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)