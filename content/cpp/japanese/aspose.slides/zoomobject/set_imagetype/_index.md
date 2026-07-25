---
title: set_ImageType()
second_title: C++ 用 Aspose.Slides API リファレンス
description: "ズーム オブジェクトの画像タイプを設定します。ZoomImageType を書き込みます。デフォルト値: Preview"
type: docs
weight: 14
url: /ja/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) メソッド


Zoom オブジェクトの画像タイプを設定します。Write [ZoomImageType](../../zoomimagetype/). デフォルト値: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## 備考


Zoom オブジェクトがスライド プレビューを使用しているか、カバー画像を使用しているかを指定します。

次の例は Image Type を Preview 値に変更することを示します。この場合、Zoom オブジェクトの現在の画像がスライド画像に変更されます: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## 参照

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)