---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides C++ API 参考
description: 创建一个新的 Summary Zoom 框架并将其添加到形状集合的末尾。
type: docs
weight: 144
url: /zh/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) 方法

创建一个新的 Summary Zoom 框架并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新 Summary Zoom 框架的 x 坐标，单位为点。 |
| y | **float** | 新 Summary Zoom 框架的 y 坐标，单位为点。 |
| width | **float** | 新 Summary Zoom 框架的宽度，单位为点。 |
| height | **float** | 新 Summary Zoom 框架的高度，单位为点。 |

### 返回值

新创建的 [ISummaryZoomFrame](../../isummaryzoomframe/)。

## 备注

此方法创建一个 Summary Zoom 框架，用于聚合演示文稿中所有章节的摘要链接。

此示例演示了将 Summary Zoom 对象添加到集合的末尾（假设在 "Presentation.pptx" 演示文稿中至少有两个章节）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISummaryZoomFrame](../../isummaryzoomframe/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)