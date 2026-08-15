---
title: get_TargetSlide()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得 Slide Zoom 物件所連結的投影片物件。請參閱 ISlide.
type: docs
weight: 1
url: /zh-hant/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() 方法

取得 [Slide](../../slide/) Zoom 物件所連結的投影片物件。請參閱 [ISlide](../../islide/)。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## 備註

以下範例示範變更目標投影片並為 [Slide](../../slide/) Zoom 物件建立新的影像：

```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlide](../../islide/)
* 類別 [ZoomFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)