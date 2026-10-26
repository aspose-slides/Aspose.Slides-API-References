---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides C++ API 參考
description: 在布局投影片中新增一個占位圖形以容納 SmartArt 圖表。
type: docs
weight: 92
url: /zh-hant/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) method


在布局投影片中新增一個占位圖形以容納 [SmartArt](../../../aspose.slides.smartart/) 圖表。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | **float** | 新占位圖形的 X 座標。 |
| y | **float** | 新占位圖形的 Y 座標。 |
| width | **float** | 新占位圖形的寬度。 |
| height | **float** | 新占位圖形的高度。 |

### 傳回值

已建立帶有 [SmartArt](../../../aspose.slides.smartart/) 占位符的 [IAutoShape](../../iautoshape/)。

## 備註



以下範例說明如何將 [SmartArt](../../../aspose.slides.smartart/) 占位圖形新增至布局投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)