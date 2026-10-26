---
title: InsertTable()
second_title: Aspose.Slides for C++ API 参考
description: 在指定索引处创建一个新表并将其插入形状集合中。
type: docs
weight: 443
url: /zh/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) 方法

创建一个新表并将其插入到指定索引处的形状集合中。

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 在插入表格时的零基索引。 |
| x | **float** | 表格的 x 坐标，单位为点。 |
| y | **float** | 表格的 y 坐标，单位为点。 |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 一个双精度数组，表示表格列的宽度，单位为点。 |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 一个双精度数组，表示表格行的高度，单位为点。 |

### 返回值

新创建的 [ITable](../../itable/)。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ITable](../../itable/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)