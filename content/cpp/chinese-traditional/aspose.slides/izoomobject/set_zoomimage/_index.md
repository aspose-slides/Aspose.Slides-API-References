---
title: set_ZoomImage()
second_title: Aspose.Slides for C++ API 參考
description: 設定縮放物件的影像。寫入 IPPImage.
type: docs
weight: 92
url: /zh-hant/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) method


設定縮放物件的影像。寫入 [IPPImage](../../ippimage/).

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
```

## 備註


此範例示範如何變更 Zoom 物件的影像：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPPImage](../../ippimage/)
* 類別 [IZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)