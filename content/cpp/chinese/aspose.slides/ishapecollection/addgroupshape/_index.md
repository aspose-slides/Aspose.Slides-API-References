---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新的空组形状并将其添加到形状集合的末尾。组\\u2019s 框架会自动调整以适应添加到其中的任何形状。
type: docs
weight: 352
url: /zh/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() 方法

创建一个新的空组形状并将其添加到形状集合的末尾。组\\u2019s 框架会自动调整以适应添加到其中的任何形状。

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### 返回值

新创建的 [IGroupShape](../../igroupshape/)。

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) 方法

创建一个新的组形状，将指定的 SVG 图像转换为单个形状，并将生成的组添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | 包含向量内容以转换为形状的 [ISvgImage](../../isvgimage/)。 |
| x | **float** | 组框的 x 坐标，单位为点。 |
| y | **float** | 组框的 y 坐标，单位为点。 |
| width | **float** | 组框的宽度，单位为点。 |
| height | **float** | 组框的高度，单位为点。 |

### 返回值

新创建的 [IGroupShape](../../igroupshape/)。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IGroupShape](../../igroupshape/)
* 类 [IShapeCollection](../)
* 类 [ISvgImage](../../isvgimage/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)