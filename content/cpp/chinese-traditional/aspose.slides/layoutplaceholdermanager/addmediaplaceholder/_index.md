---
title: AddMediaPlaceholder()
second_title: Aspose.Slides for C++ API 參考文件
description: 將新的佔位形狀新增至版面投影片，用於容納媒體物件。
type: docs
weight: 105
url: /zh-hant/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) 方法

將新的佔位形狀新增至版面投影片，用於容納媒體物件。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | **float** | 新佔位形狀的 X 座標。 |
| y | **float** | 新佔位形狀的 Y 座標。 |
| width | **float** | 新佔位形狀的寬度。 |
| height | **float** | 新佔位形狀的高度。 |

### 回傳值

已建立 [IAutoShape](../../iautoshape/)，其中包含 Media 佔位符。

## 備註

以下範例說明如何將 Media 佔位形狀新增至版面投影片。
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [LayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)