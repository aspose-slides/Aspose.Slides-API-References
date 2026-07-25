---
title: set_TileOffsetY()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャの垂直オフセットをシェイプの原点からポイント単位で設定します。正の値はテクスチャを下に移動し、負の値は上に移動します。floatを書き込みます。
type: docs
weight: 313
url: /ja/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) メソッド


テクスチャの垂直オフセットをシェイプの原点からポイント単位で設定します。正の値はテクスチャを下に移動し、負の値は上に移動します。**float**を書き込みます。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプのピクチャーフィル形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャーフィルモードをTileに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの垂直オフセットを-50ポイントに設定します
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## 参照

* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)