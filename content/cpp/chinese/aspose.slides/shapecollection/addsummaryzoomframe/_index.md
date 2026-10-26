---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新的 Summary Zoom 框架并将其添加到形状集合的末尾。
type: docs
weight: 157
url: /zh/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) 方法

创建一个新的 Summary Zoom 框架并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新的 Summary Zoom 框架的 x 坐标，以点为单位。 |
| y | **float** | 新的 Summary Zoom 框架的 y 坐标，以点为单位。 |
| width | **float** | 新的 Summary Zoom 框架的宽度，以点为单位。 |
| height | **float** | 新的 Summary Zoom 框架的高度，以点为单位。 |

### 返回值

新创建的 [ISummaryZoomFrame](../../isummaryzoomframe/)。

## 备注

此方法创建一个新的 Summary Zoom，并将对象集合放入其中，以适用于此演示文稿中的所有章节。

此示例演示了向集合末尾添加 Summary Zoom 对象 (假设在 "Presentation.pptx" 演示文稿中至少有两个章节)： 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISummaryZoomFrame](../../isummaryzoomframe/)
* 类 [ShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)