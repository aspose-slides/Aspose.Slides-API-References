---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新的空组形状，并将其添加到形状集合的末尾。group\\u2019s 框架会自动调整以适应添加的任何形状。
type: docs
weight: 391
url: /zh/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() 方法

创建一个新的空组形状，并将其添加到形状集合的末尾。group\u2019s 框架会自动调整以适应添加的任何形状。

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### 返回值

新创建的[IGroupShape](../../igroupshape/)。

## 备注

下面的示例展示了如何将组形状添加到 PowerPoint [Presentation](../../presentation/) 的幻灯片中。

```cpp
// 实例化 Presentation 类
auto pres = System::MakeObject<Presentation>();

// 获取第一张幻灯片
auto slide = pres->get_Slides()->idx_get(0);
// 访问幻灯片的形状集合
auto slideShapes = slide->get_Shapes();
// 向幻灯片添加组形状
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// 在添加的组形状内部添加形状
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// 添加组形状框架
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// 将 PPTX 文件写入磁盘
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) 方法

创建一个新的组形状，将指定的 SVG 图像转换为单独的形状，并将生成的组添加到形状集合的末尾。

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | 包含要转换为形状的向量内容的[ISvgImage](../../isvgimage/)。 |
| x | **float** | group\u2019s 框架的 x 坐标（单位：点）。 |
| y | **float** | group\u2019s 框架的 y 坐标（单位：点）。 |
| width | **float** | group\u2019s 框架的宽度（单位：点）。 |
| height | **float** | group\u2019s 框架的高度（单位：点）。 |

### 返回值

新创建的[IGroupShape](../../igroupshape/)。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IGroupShape](../../igroupshape/)
* 类 [ShapeCollection](../)
* 类 [ISvgImage](../../isvgimage/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)