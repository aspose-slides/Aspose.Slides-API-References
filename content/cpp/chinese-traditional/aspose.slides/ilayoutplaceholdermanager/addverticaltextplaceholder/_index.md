---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides for C++ API 參考手冊
description: 將新的占位符形狀新增至版面投影片，以垂直方向容納文字內容。
type: docs
weight: 40
url: /zh-hant/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) 方法

將新的占位符形狀新增至版面投影片，以垂直方向容納文字內容。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | **float** | 新占位符形狀的 X 座標。 |
| y | **float** | 新占位符形狀的 Y 座標。 |
| width | **float** | 新占位符形狀的寬度。 |
| height | **float** | 新占位符形狀的高度。 |

### 返回值

已建立帶有文字（垂直）占位符的 [IAutoShape](../../iautoshape/)。

## 備註

以下範例示範如何將文字（垂直）占位符形狀新增至版面投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [ILayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)