---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides C++ API 參考文件
description: 將新的佔位圖形新增至版面投影片，以放置線上影像。
type: docs
weight: 118
url: /zh-hant/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) 方法

新增一個佔位圖形到版面投影片，以放置線上影像。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | **float** | 新佔位圖形的 X 座標。 |
| y | **float** | 新佔位圖形的 Y 座標。 |
| width | **float** | 新佔位圖形的寬度。 |
| height | **float** | 新佔位圖形的高度。 |

### 回傳值

已建立 [IAutoShape](../../iautoshape/) 具線上影像佔位符。

## 備註

以下範例示範如何將線上影像佔位圖形加入版面投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [LayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)