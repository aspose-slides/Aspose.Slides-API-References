---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides for C++ API 參考
description: 將新增一個占位形狀至佈局投影片，用於保存線上圖像。
type: docs
weight: 118
url: /zh-hant/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) 方法

在佈局投影片中新增一個占位形狀以保存線上圖像。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新占位形狀的 X 座標。 |
| y | **float** | 新占位形狀的 Y 座標。 |
| width | **float** | 新占位形狀的寬度。 |
| height | **float** | 新占位形狀的高度。 |

### 返回值

已建立 [IAutoShape](../../iautoshape/)，其為線上圖像占位符。

## 備註

以下範例說明如何將線上圖像占位符形狀新增至佈局投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [ILayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)