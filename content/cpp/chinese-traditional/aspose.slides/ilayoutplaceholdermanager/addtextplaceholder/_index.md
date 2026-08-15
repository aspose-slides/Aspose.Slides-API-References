---
title: AddTextPlaceholder()
second_title: Aspose.Slides C++ API 參考
description: 將新的佔位形狀新增至版面投影片，以容納文字內容。
type: docs
weight: 27
url: /zh-hant/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) 方法


將新的佔位形狀新增到版面投影片中，以容納文字內容。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新佔位形狀的 X 座標。 |
| y | **float** | 新佔位形狀的 Y 座標。 |
| width | **float** | 新佔位形狀的寬度。 |
| height | **float** | 新佔位形狀的高度。 |

### 回傳值

已建立 [IAutoShape](../../iautoshape/)，並包含 Text 佔位。
## 備註



以下範例說明如何將 Text 佔位形狀新增到版面投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [ILayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)