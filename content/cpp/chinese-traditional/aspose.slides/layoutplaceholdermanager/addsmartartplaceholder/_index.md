---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides for C++ API 參考
description: 在版面投影片中新增一個佔位形狀以容納 SmartArt 圖表。
type: docs
weight: 92
url: /zh-hant/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) 方法

在版面投影片中新增一個佔位形狀以容納 [SmartArt](../../../aspose.slides.smartart/) 圖表。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新佔位形狀的 X 座標。 |
| y | **float** | 新佔位形狀的 Y 座標。 |
| width | **float** | 新佔位形狀的寬度。 |
| height | **float** | 新佔位形狀的高度。 |

### 傳回值

已建立 [IAutoShape](../../iautoshape/)，帶有一個 [SmartArt](../../../aspose.slides.smartart/) 佔位。

## 備註



以下範例說明如何將 [SmartArt](../../../aspose.slides.smartart/) 佔位形狀加入版面投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [LayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)