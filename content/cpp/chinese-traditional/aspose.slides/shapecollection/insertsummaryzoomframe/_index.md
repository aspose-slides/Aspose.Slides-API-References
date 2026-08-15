---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的 Summary Zoom 框架，並將其插入到指定索引的形狀集合中。
type: docs
weight: 170
url: /zh-hant/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) 方法

建立一個新的 Summary Zoom 框架，並將其插入到指定索引的形狀集合中。

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入 Summary Zoom 框架的零基索引。 |
| x | **float** | 新 Summary Zoom 框架的 x 座標，單位為點。 |
| y | **float** | 新 Summary Zoom 框架的 y 座標，單位為點。 |
| width | **float** | 新 Summary Zoom 框架的寬度，單位為點。 |
| height | **float** | 新 Summary Zoom 框架的高度，單位為點。 |

### 返回值

新建立的 [ISummaryZoomFrame](../../isummaryzoomframe/)。

## 備註


此方法會建立一個 Summary Zoom 框架，彙總簡報中所有章節的摘要連結。

此範例示範在集合的指定索引處建立並插入 Summary Zoom 物件（假設 "Presentation.pptx" 簡報中至少有兩個章節）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomFrame](../../isummaryzoomframe/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)