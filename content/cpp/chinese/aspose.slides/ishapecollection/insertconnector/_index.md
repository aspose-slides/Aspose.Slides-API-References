---
title: InsertConnector()
second_title: Aspose.Slides C++ API 参考
description: 创建一个新的连接器形状并将其插入到指定索引的形状集合中，同时应用默认模板样式。
type: docs
weight: 391
url: /zh/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) 方法

创建一个新的连接器形状并将其插入到指定索引的形状集合中，同时应用默认模板样式。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入连接器形状的零基索引。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入的连接器形状的 [ShapeType](../../shapetype/)。 |
| x | **float** | 连接器框架的 x 坐标（单位为点）。 |
| y | **float** | 连接器框架的 y 坐标（单位为点）。 |
| width | **float** | 连接器框架的宽度（单位为点）。 |
| height | **float** | 连接器框架的高度（单位为点）。 |

### 返回值

新创建的 [IConnector](../../iconnector/)。

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) 方法

创建一个新的连接器形状并将其插入到指定索引的形状集合中，可选择性地应用默认模板样式。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入连接器形状的零基索引。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入的连接器形状的 [ShapeType](../../shapetype/)。 |
| x | **float** | 连接器框架的 x 坐标（单位为点）。 |
| y | **float** | 连接器框架的 y 坐标（单位为点）。 |
| width | **float** | 连接器框架的宽度（单位为点）。 |
| height | **float** | 连接器框架的高度（单位为点）。 |
| createFromTemplate | **bool** | True 表示应用默认模板样式（非空名称，简易样式）；false 表示使用默认属性值创建连接器。 |

### 返回值

新创建的 [IConnector](../../iconnector/)。

## 另请参见

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)