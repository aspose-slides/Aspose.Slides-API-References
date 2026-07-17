---
title: InsertAutoShape()
second_title: Aspose.Slides C++ API 参考
description: 创建一个新的自动形状并将其插入到指定索引的形状集合中，应用默认模板格式。
type: docs
weight: 378
url: /zh/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) 方法

创建一个新的自动形状并将其插入到指定索引的形状集合中，应用默认模板格式。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入新自动形状的零基索引。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入的自动形状的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形状框架的 x 坐标，单位为点。 |
| y | **float** | 形状框架的 y 坐标，单位为点。 |
| width | **float** | 形状框架的宽度，单位为点。 |
| height | **float** | 形状框架的高度，单位为点。 |

### 返回值

新创建的 [IAutoShape](../../iautoshape/)。

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) 方法

创建一个新的自动形状并将其插入到指定索引的形状集合中，可选择使用默认模板样式进行初始化。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入自动形状的零基索引。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入的自动形状的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形状框架的 x 坐标，单位为点。 |
| y | **float** | 形状框架的 y 坐标，单位为点。 |
| width | **float** | 形状框架的宽度，单位为点。 |
| height | **float** | 形状框架的高度，单位为点。 |
| createFromTemplate | **bool** | True 表示应用默认模板样式（包括非空名称、简易样式和居中文本）；false 表示创建形状时所有属性均设为默认值。 |

### 返回值

新创建的 [IAutoShape](../../iautoshape/)。

## 另请参见

* 枚举 [ShapeType](../../shapetype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [ShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)