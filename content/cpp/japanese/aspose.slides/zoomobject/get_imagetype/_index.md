---
title: get_ImageType()
second_title: Aspose.Slides for C++ API リファレンス
description: "ズームオブジェクトの画像タイプを取得します。ZoomImageType を参照してください。デフォルト値: Preview"
type: docs
weight: 1
url: /ja/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() メソッド

ズームオブジェクトの画像タイプを取得します。参照してください [ZoomImageType](../../zoomimagetype/)。デフォルト値: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## 備考

Zoomオブジェクトがスライドプレビューを使用しているか、カバー画像を使用しているかを指定します。

次の例は、Image Type を Preview 値に変更することを示します。この場合、Zoomオブジェクトの現在の画像がスライド画像に変更されます:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## 参照

* 列挙型 [ZoomImageType](../../zoomimagetype/)
* クラス [ZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)