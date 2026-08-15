---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides C++ 版 API 參考
description: 在版面投影片中新增一個佔位形狀，以垂直方向容納內容，例如圖片、表格、媒體或文字。
type: docs
weight: 14
url: /zh-hant/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) 方法

在版面投影片中新增一個佔位形狀，以垂直方向容納內容，例如圖片、表格、媒體或文字。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新佔位形狀的 X 座標。 |
| y | **float** | 新佔位形狀的 Y 座標。 |
| width | **float** | 新佔位形狀的寬度。 |
| height | **float** | 新佔位形狀的高度。 |

### 回傳值

已建立 [IAutoShape](../../iautoshape/)，並包含 Content (Vertical) 佔位。

## 備註

以下範例說明如何將 Content (Vertical) 佔位形狀新增至版面投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [LayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)