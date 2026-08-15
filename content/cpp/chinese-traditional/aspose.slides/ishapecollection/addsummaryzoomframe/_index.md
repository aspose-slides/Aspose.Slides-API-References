---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的 Summary Zoom 框架，並將其新增至形狀集合的末端。
type: docs
weight: 144
url: /zh-hant/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) 方法

建立一個新的 Summary Zoom 框架，並將其新增至形狀集合的末端。

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新 Summary Zoom 框架的 x 座標，單位為點。 |
| y | **float** | 新 Summary Zoom 框架的 y 座標，單位為點。 |
| width | **float** | 新 Summary Zoom 框架的寬度，單位為點。 |
| height | **float** | 新 Summary Zoom 框架的高度，單位為點。 |

### 回傳值

剛剛建立的 [ISummaryZoomFrame](../../isummaryzoomframe/)。

## 備註

此方法會建立一個 Summary Zoom 框架，彙總簡報中所有章節的摘要連結。

此範例示範如何將 Summary Zoom 物件新增至集合的末端（假設在 "Presentation.pptx" 簡報中至少有兩個章節）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomFrame](../../isummaryzoomframe/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)