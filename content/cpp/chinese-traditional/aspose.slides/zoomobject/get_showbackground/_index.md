---
title: get_ShowBackground()
second_title: Aspose.Slides for C++ API 參考
description: "取得指定 Zoom 是否使用目標投影片背景的值。讀取 bool。預設值：true"
type: docs
weight: 53
url: /zh-hant/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() 方法

取得指定 Zoom 是否使用目標投影片背景的值。讀取 **bool**。預設值：true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## 備註

此範例示範如何移除 Zoom 物件圖像的背景：
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## 另見

* 類別 [ZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)