---
title: get_TileOffsetX()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャの水平方向のオフセットを、シェイプの原点からポイント単位で返します。正の値はテクスチャを右に移動し、負の値は左に移動します。float を読み取ります。
type: docs
weight: 274
url: /ja/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() メソッド

テクスチャの水平方向のオフセットを、シェイプの原点からポイント単位で返します。正の値はテクスチャを右方向に移動し、負の値は左方向に移動します。読み取り **float**。

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプのピクチャーフィル形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャーフィルモードを Tile に設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの水平方向オフセットを 20 ポイントに設定します
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 参照

* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)