---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个带有默认格式的自动形状并将其添加到形状集合的末尾。
type: docs
weight: 313
url: /zh/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) 方法

创建一个新的自动形状，使用默认格式，并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要添加的自动形状的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形状框的 x 坐标，单位为点。 |
| y | **float** | 形状框的 y 坐标，单位为点。 |
| width | **float** | 形状框的宽度，单位为点。 |
| height | **float** | 形状框的高度，单位为点。 |

### 返回值

新创建的 [IAutoShape](../../iautoshape/)。

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) 方法

创建一个新的自动形状并将其添加到形状集合的末尾，可选地使用默认模板格式进行初始化。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要添加的自动形状的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形状框的 x 坐标，单位为点。 |
| y | **float** | 形状框的 y 坐标，单位为点。 |
| width | **float** | 形状框的宽度，单位为点。 |
| height | **float** | 形状框的高度，单位为点。 |
| createFromTemplate | **bool** | 若为 true，则将默认模板样式（简易样式、居中文本和非空名称）应用于新形状；若为 false，则创建形状时所有属性均设置为默认值。 |

### 返回值

新创建的 [IAutoShape](../../iautoshape/)。

## 另请参见

* 枚举 [ShapeType](../../shapetype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)