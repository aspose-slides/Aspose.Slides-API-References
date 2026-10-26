---
title: AddChartPlaceholder()
second_title: Aspose.Slides for C++ API 參考
description: 在版面配置投影片上新增一個佔位形狀以容納圖表。
type: docs
weight: 66
url: /zh-hant/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) method

在佈局投影片上新增一個佔位形狀以容納 Chart。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```

### Arguments

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | **float** | 新佔位形狀的 X 坐標。 |
| y | **float** | 新佔位形狀的 Y 坐標。 |
| width | **float** | 新佔位形狀的寬度。 |
| height | **float** | 新佔位形狀的高度。 |

### Return Value

已建立 [IAutoShape](../../iautoshape/)，其中包含 Chart 佔位符。

## Remarks

以下範例說明如何將 Chart 佔位形狀新增至佈局投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## See Also

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [ILayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)