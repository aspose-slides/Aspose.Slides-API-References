---
title: set_ShowBackground()
second_title: Aspose.Slides C++ API 參考文件
description: "設定指定 Zoom 是否使用目的投影片背景的值。寫入 bool。預設值： true"
type: docs
weight: 66
url: /zh-hant/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) 方法

設定決定 Zoom 是否使用目的投影片背景的值。寫入 **bool**。預設值： true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## 備註

本範例示範如何移除 Zoom 物件之影像的背景：

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