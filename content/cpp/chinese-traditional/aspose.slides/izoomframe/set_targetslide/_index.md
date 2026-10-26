---
title: set_TargetSlide()
second_title: Aspose.Slides 的 C++ API 參考
description: 設定 Slide Zoom 物件所連結的投影片物件。寫入 ISlide.
type: docs
weight: 14
url: /zh-hant/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) 方法


設定 [Slide](../../slide/) Zoom 物件所連結的投影片物件。寫入 [ISlide](../../islide/)。

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## 備註


以下範例示範變更目標投影片並為 [Slide](../../slide/) Zoom 物件建立新影像：
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlide](../../islide/)
* 類別 [IZoomFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)