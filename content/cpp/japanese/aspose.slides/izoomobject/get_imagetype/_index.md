---
title: get_ImageType()
second_title: Aspose.Slides for C++ API リファレンス
description: "ズーム オブジェクトの画像タイプを取得します。ZoomImageType を参照してください。デフォルト値: Preview"
type: docs
weight: 1
url: /ja/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() method


ズーム オブジェクトの画像タイプを取得します。[ZoomImageType](../../zoomimagetype/) を参照してください。デフォルト値: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## 備考


Zoom オブジェクトがスライド プレビューを使用しているか、カバー画像を使用しているかを指定します。

この例では、Image Type を Preview 値に変更する方法を示します。この場合、Zoom オブジェクトの現在の画像はスライド画像に変更されます: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## 参照

* Enum [ZoomImageType](../../zoomimagetype/)
* クラス [IZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)