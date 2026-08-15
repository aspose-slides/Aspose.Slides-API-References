---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides C++ API 參考手冊
description: 建立一個新的 Summary Zoom 框架，並將其新增至圖形集合的末尾。
type: docs
weight: 157
url: /zh-hant/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) 方法

建立一個新的 Summary Zoom 框架，並將其新增至形狀集合的末尾。

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新 Summary Zoom 框架的 x 坐標，單位為點。 |
| y | **float** | 新 Summary Zoom 框架的 y 坐標，單位為點。 |
| width | **float** | 新 Summary Zoom 框架的寬度，單位為點。 |
| height | **float** | 新 Summary Zoom 框架的高度，單位為點。 |

### 傳回值

新建立的 [ISummaryZoomFrame](../../isummaryzoomframe/)。

## 備註

此方法建立一個新的 Summary Zoom，並將此簡報中所有節的物件集合放入其中。  

此範例示範將 Summary Zoom 物件新增至集合的末尾（假設在 \"Presentation.pptx\" 簡報中至少有兩個節）：

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomFrame](../../isummaryzoomframe/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)