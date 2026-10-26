---
title: set_ZoomImage()
second_title: Aspose.Slides for C++ API リファレンス
description: ズームオブジェクトの画像を設定します。IPPImageを書き込みます。
type: docs
weight: 92
url: /ja/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) メソッド

ズームオブジェクトの画像を設定します。[IPPImage](../../ippimage/)を書き込みます。

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## 備考

この例では、Zoomオブジェクトの画像を変更する方法を示します。
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