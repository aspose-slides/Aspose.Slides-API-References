---
title: AddContentPlaceholder()
second_title: Aspose.Slides for C++ API 參考
description: 將新的占位形狀新增至布局投影片，以容納內容，例如圖片、表格、媒體或文字。
type: docs
weight: 1
url: /zh-hant/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) 方法


將新的占位形狀新增至布局投影片，以容納內容，例如圖片、表格、媒體或文字。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | **float** | 新占位形狀的 X 座標。 |
| y | **float** | 新占位形狀的 Y 座標。 |
| width | **float** | 新占位形狀的寬度。 |
| height | **float** | 新占位形狀的高度。 |

### 回傳值

已建立帶有內容占位的 [IAutoShape](../../iautoshape/)。

## 備註



以下範例說明如何將內容占位形狀新增至布局投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 另見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [ILayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)