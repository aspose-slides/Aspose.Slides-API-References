---
title: get_TargetSlide()
second_title: Aspose.Slides C++ API 參考
description: 取得 Slide Zoom 物件所連結的投影片物件。請參閱 ISlide.
type: docs
weight: 1
url: /zh-hant/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() 方法

取得 [Slide](../../slide/) Zoom 物件所連結的投影片物件。請參閱 [ISlide](../../islide/)。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## 備註

以下範例示範變更目標投影片並為 [Slide](../../slide/) Zoom 物件建立新圖像：
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## 另請參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlide](../../islide/)
* 類別 [IZoomFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)