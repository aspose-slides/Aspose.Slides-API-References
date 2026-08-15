---
title: set_ZoomImage()
second_title: Aspose.Slides for C++ API 參考
description: 設定放大物件的圖像。寫入 IPPImage.
type: docs
weight: 92
url: /zh-hant/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) 方法

設定放大物件的圖像。Write [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## 備註


此範例示範變更 Zoom 物件的圖像：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPPImage](../../ippimage/)
* 類別 [ZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)