---
title: AddTablePlaceholder()
second_title: Aspose.Slides for C++ API 參考
description: 在版面投影片中新增一個佔位形狀以放置表格。
type: docs
weight: 79
url: /zh-hant/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) 方法

在版面投影片中新增一個佔位形狀以放置表格。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新佔位形狀的 X 座標。 |
| y | **float** | 新佔位形狀的 Y 座標。 |
| width | **float** | 新佔位形狀的寬度。 |
| height | **float** | 新佔位形狀的高度。 |

### 返回值

已建立 [IAutoShape](../../iautoshape/)，並使用 [Table](../../table/) 佔位符。

## 備註

以下範例說明如何將 [Table](../../table/) 佔位形狀新增至版面投影片。
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [ILayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)