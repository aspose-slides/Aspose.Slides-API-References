---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個新的 Summary Zoom 框架，並將其插入到形狀集合中指定的索引位置。
type: docs
weight: 157
url: /zh-hant/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) 方法

建立一個新的 Summary Zoom 框架，並將其插入到形狀集合中指定的索引位置。

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 在插入 Summary Zoom 框架時使用的從零開始的索引。 |
| x | **float** | 新 Summary Zoom 框架的 x 坐標（單位：點）。 |
| y | **float** | 新 Summary Zoom 框架的 y 坐標（單位：點）。 |
| width | **float** | 新 Summary Zoom 框架的寬度（單位：點）。 |
| height | **float** | 新 Summary Zoom 框架的高度（單位：點）。 |

### 返回值

新建立的 [ISummaryZoomFrame](../../isummaryzoomframe/)。

## 備註

此方法建立一個 Summary Zoom 框架，彙總演示文稿中所有章節的摘要連結。

以下範例示範如何在集合的指定索引位置建立並插入 Summary Zoom 物件（假設在 "Presentation.pptx" 演示文稿中至少有兩個章節）：

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomFrame](../../isummaryzoomframe/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)