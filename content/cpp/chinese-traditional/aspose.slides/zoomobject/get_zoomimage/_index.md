---
title: get_ZoomImage()
second_title: Aspose.Slides for C++ API 參考
description: 取得縮放物件的圖像。請閱讀 IPPImage.
type: docs
weight: 79
url: /zh-hant/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() 方法

取得縮放物件的圖像。請閱讀 [IPPImage](../../ippimage/)。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## 備註

此範例示範變更 Zoom 物件的圖像：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IPPImage](../../ippimage/)
* 類別 [ZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)