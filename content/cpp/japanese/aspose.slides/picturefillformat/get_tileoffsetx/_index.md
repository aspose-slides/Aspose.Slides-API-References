---
title: get_TileOffsetX()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャの水平オフセット（ポイント）をシェイプの原点から返します。正の値はテクスチャを右に移動させ、負の値は左に移動させます。読み取り float.
type: docs
weight: 274
url: /ja/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() メソッド

テクスチャの水平オフセット（ポイント）をシェイプの原点から返します。正の値はテクスチャを右に移動させ、負の値は左に移動させます。読み取り **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプの画像塗りつぶし形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 画像塗りつぶしモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの水平オフセットを 20 ポイントに設定します
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 参照

* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)