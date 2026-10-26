---
title: get_ZoomImage()
second_title: Aspose.Slides for C++ API リファレンス
description: ズームオブジェクトの画像を取得します。IPPImage を参照してください。
type: docs
weight: 79
url: /ja/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() メソッド

ズームオブジェクトの画像を取得します。[IPPImage](../../ippimage/) を参照してください。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## 備考

この例は Zoom オブジェクトの画像の変更を示しています:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPPImage](../../ippimage/)
* クラス [IZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)