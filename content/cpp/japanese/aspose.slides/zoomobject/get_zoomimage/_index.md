---
title: get_ZoomImage()
second_title: Aspose.Slides for C++ API リファレンス
description: ズームオブジェクトの画像を取得します。IPPImage を参照してください。
type: docs
weight: 79
url: /ja/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() メソッド

ズームオブジェクトの画像を取得します。[IPPImage](../../ippimage/) を参照してください。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## 備考

この例は、Zoom オブジェクトの画像の変更を示しています: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPPImage](../../ippimage/)
* クラス [ZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)