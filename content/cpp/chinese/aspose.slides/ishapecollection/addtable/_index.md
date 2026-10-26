---
title: AddTable()
second_title: Aspose.Slides C++ API 参考
description: 创建一个新表并将其添加到形状集合的末尾。
type: docs
weight: 430
url: /zh/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) 方法


创建一个新表并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 表的 x 坐标，单位为点。 |
| y | **float** | 表的 y 坐标，单位为点。 |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 一个 double 数组，表示表格列的宽度，单位为点。 |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 一个 double 数组，表示表格行的高度，单位为点。 |

### 返回值

新创建的 [ITable](../../itable/)。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ITable](../../itable/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)