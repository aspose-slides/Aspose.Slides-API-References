---
title: set_ShowBackground()
second_title: Aspose.Slides for C++ API 參考文件
description: "設定指定 Zoom 是否使用目標投影片背景的值。寫入 bool。預設值：true"
type: docs
weight: 66
url: /zh-hant/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) 方法


設定指定 Zoom 是否使用目標投影片背景的值。寫入 **bool**。預設值：true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
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