---
title: AddAutoShape()
second_title: Aspose.Slides C++ API 参考
description: 创建一个具有默认格式的新自动形状，并将其添加到形状集合的末尾。
type: docs
weight: 352
url: /zh/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) method

创建一个具有默认格式的新自动形状并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要添加的自动形状的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形状\\u2019s 框架的 x 坐标，单位为点。 |
| y | **float** | 形状\\u2019s 框架的 y 坐标，单位为点。 |
| width | **float** | 形状\\u2019s 框架的宽度，单位为点。 |
| height | **float** | 形状\\u2019s 框架的高度，单位为点。 |

### 返回值

新创建的 [IAutoShape](../../iautoshape/)。

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) method

创建一个新自动形状并将其添加到形状集合的末尾，可选地使用默认模板格式进行初始化。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要添加的自动形状的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形状\\u2019s 框架的 x 坐标，单位为点。 |
| y | **float** | 形状\\u2019s 框架的 y 坐标，单位为点。 |
| width | **float** | 形状\\u2019s 框架的宽度，单位为点。 |
| height | **float** | 形状\\u2019s 框架的高度，单位为点。 |
| createFromTemplate | **bool** | True 表示对新形状应用默认模板样式（简单样式、居中文本和非空名称）；false 表示以所有属性均为默认值的方式创建形状。 |

### 返回值

新创建的 [IAutoShape](../../iautoshape/)。

## 另请参阅

* 枚举 [ShapeType](../../shapetype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [ShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)