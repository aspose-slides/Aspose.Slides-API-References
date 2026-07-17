---
title: AddConnector()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个具有默认模板样式的新连接器形状，并将其添加到形状集合的末尾。
type: docs
weight: 417
url: /zh/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) 方法

创建一个具有默认模板样式的新连接器形状，并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要添加的连接器形状的 [ShapeType](../../shapetype/)。 |
| x | **float** | 连接器框架的 x 坐标，单位为点。 |
| y | **float** | 连接器框架的 y 坐标，单位为点。 |
| width | **float** | 连接器框架的宽度，单位为点。 |
| height | **float** | 连接器框架的高度，单位为点。 |

### 返回值

新创建的 [IConnector](../../iconnector/)。

## 备注

下面的示例展示了如何在 PowerPoint [Presentation](../../presentation/) 中在两个形状（椭圆和矩形）之间添加一个连接器（弯曲连接器）。

```cpp
// 实例化一个表示 PPTX 文件的演示文稿类
auto input = System::MakeObject<Presentation>();

// 访问特定幻灯片的形状集合
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// 添加椭圆自动形状
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// 添加矩形自动形状
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// 向幻灯片形状集合添加连接器形状
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// 使用连接器连接形状
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// 调用 reroute 方法，设置形状之间的自动最短路径
connector->Reroute();

// 保存演示文稿
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) 方法

创建一个新的连接器形状并将其添加到形状集合的末尾，可选择应用默认模板样式。

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要创建的连接器形状的 [ShapeType](../../shapetype/)。 |
| x | **float** | 连接器框架的 x 坐标，单位为点。 |
| y | **float** | 连接器框架的 y 坐标，单位为点。 |
| width | **float** | 连接器框架的宽度，单位为点。 |
| height | **float** | 连接器框架的高度，单位为点。 |
| createFromTemplate | **bool** | True 以应用默认模板样式（非空名称，简单样式）；false 以使用默认属性值创建连接器。 |

### 返回值

新创建的 [IConnector](../../iconnector/)。

## 另请参见

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)