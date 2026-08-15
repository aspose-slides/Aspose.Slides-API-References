---
title: AddPicturePlaceholder()
second_title: Aspose.Slides for C++ API 參考文件
description: 將新佔位圖形新增至版面投影片中以放置圖片。
type: docs
weight: 53
url: /zh-hant/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) 方法

將新佔位圖形新增至版面投影片中以放置圖片。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新佔位圖形的 X 座標。 |
| y | **float** | 新佔位圖形的 Y 座標。 |
| width | **float** | 新佔位圖形的寬度。 |
| height | **float** | 新佔位圖形的高度。 |

### 傳回值

已建立 [IAutoShape](../../iautoshape/)，其包含 [Picture](../../picture/) 佔位符。

## 附註

以下範例說明如何將 [Picture](../../picture/) 佔位圖形新增至版面投影片。

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 相關參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [LayoutPlaceholderManager](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)