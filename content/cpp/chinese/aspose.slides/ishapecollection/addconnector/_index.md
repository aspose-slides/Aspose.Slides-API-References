---
title: AddConnector()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个带有默认模板样式的新连接器形状，并将其添加到形状集合的末尾。
type: docs
weight: 378
url: /zh/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) 方法

创建一个带有默认模板样式的新连接器形状，并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要添加的连接器形状的[ShapeType](../../shapetype/)。 |
| x | **float** | 连接器框架的 x 坐标，以点为单位。 |
| y | **float** | 连接器框架的 y 坐标，以点为单位。 |
| width | **float** | 连接器框架的宽度，以点为单位。 |
| height | **float** | 连接器框架的高度，以点为单位。 |

### 返回值

新创建的[IConnector](../../iconnector/)。

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) 方法

创建一个新连接器形状并将其添加到形状集合的末尾，可选择应用默认模板样式。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要创建的连接器形状的[ShapeType](../../shapetype/)。 |
| x | **float** | 连接器框架的 x 坐标，以点为单位。 |
| y | **float** | 连接器框架的 y 坐标，以点为单位。 |
| width | **float** | 连接器框架的宽度，以点为单位。 |
| height | **float** | 连接器框架的高度，以点为单位。 |
| createFromTemplate | **bool** | True 表示应用默认模板样式（非空名称，简单样式）；false 表示使用默认属性值创建连接器。 |

### 返回值

新创建的[IConnector](../../iconnector/)。

## 另请参阅

* 枚举 [ShapeType](../../shapetype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IConnector](../../iconnector/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)