---
title: AddContentPlaceholder()
second_title: Aspose.Slides for C++ API 參考
description: 在佈局投影片中新增一個占位符圖形，以容納內容，例如圖片、表格、媒體或文字。
type: docs
weight: 1
url: /zh-hant/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) 方法

將新的占位符形狀新增至佈局投影片，以容納內容，例如圖片、表格、媒體或文字。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新占位符形狀的 X 座標。 |
| y | **float** | 新占位符形狀的 Y 座標。 |
| width | **float** | 新占位符形狀的寬度。 |
| height | **float** | 新占位符形狀的高度。 |

### 返回值

已建立帶有 Content 占位符的 [IAutoShape](../../iautoshape/)。

## 備註

以下範例說明如何將 Content 占位符形狀新增至佈局投影片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [LayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)