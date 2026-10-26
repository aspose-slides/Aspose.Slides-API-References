---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides C++ API 参考
description: 在指定索引处创建一个新的 Summary Zoom 框架并将其插入到形状集合中。
type: docs
weight: 170
url: /zh/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) 方法


创建一个新的 Summary Zoom 框架并将其插入到指定索引处的形状集合中。

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入 Summary Zoom 框架的基于零的索引。 |
| x | **float** | 新 Summary Zoom 框架的 x 坐标，单位为点。 |
| y | **float** | 新 Summary Zoom 框架的 y 坐标，单位为点。 |
| width | **float** | 新 Summary Zoom 框架的宽度，单位为点。 |
| height | **float** | 新 Summary Zoom 框架的高度，单位为点。 |

### 返回值

新创建的 [ISummaryZoomFrame](../../isummaryzoomframe/)。
## 备注


此方法创建一个 Summary Zoom 框架，用于聚合演示文稿中所有章节的摘要链接。

此示例演示了在集合的指定索引处创建并插入 Summary Zoom 对象（假设 "Presentation.pptx" 演示文稿中至少有两个章节）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)