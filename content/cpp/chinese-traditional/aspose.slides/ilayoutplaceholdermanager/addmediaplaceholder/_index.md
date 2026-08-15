---
title: AddMediaPlaceholder()
second_title: Aspose.Slides for C++ API 參考文件
description: 將新佔位圖形新增至版面投影片，以容納媒體物件。
type: docs
weight: 105
url: /zh-hant/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---
## ILayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) 方法

新增一個佔位圖形到版面投影片，以容納媒體物件。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新佔位形狀的 X 座標。 |
| y | **float** | 新佔位形狀的 Y 座標。 |
| width | **float** | 新佔位形狀的寬度。 |
| height | **float** | 新佔位形狀的高度。 |

### 傳回值

已建立 [IAutoShape](../../iautoshape/)，其中包含媒體佔位元。

## 備註

以下範例示範如何將媒體佔位形狀新增至佈局投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [ILayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)