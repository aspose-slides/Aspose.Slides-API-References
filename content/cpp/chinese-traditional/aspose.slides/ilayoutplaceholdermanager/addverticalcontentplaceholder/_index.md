---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides for C++ API 參考文件
description: 在版面投影片中新增一個佔位形狀，用於以垂直方向保存內容，例如圖片、表格、媒體或文字。
type: docs
weight: 14
url: /zh-hant/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) 方法

在版面投影片中新增一個佔位形狀，用於以垂直方向保存內容，例如圖片、表格、媒體或文字。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新佔位形狀的 X 座標。 |
| y | **float** | 新佔位形狀的 Y 座標。 |
| width | **float** | 新佔位形狀的寬度。 |
| height | **float** | 新佔位形狀的高度。 |

### 傳回值

已建立具有內容（垂直）佔位的 [IAutoShape](../../iautoshape/)。

## 備註

以下範例說明如何將內容（垂直）佔位形狀新增至版面投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)