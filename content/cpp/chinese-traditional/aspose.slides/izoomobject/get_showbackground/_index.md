---
title: get_ShowBackground()
second_title: Aspose.Slides for C++ API 參考
description: "取得指定 Zoom 是否使用目標投影片背景的值。讀取 bool。預設值：true"
type: docs
weight: 53
url: /zh-hant/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() method


取得指定 Zoom 是否使用目標投影片背景的值。讀取 **bool**。預設值：true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## 備註


此範例示範移除 Zoom 物件影像的背景：
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## 另請參閱

* 類別 [IZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)