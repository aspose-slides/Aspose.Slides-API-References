---
title: set_TileOffsetX()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャの水平オフセットをシェイプの原点からポイント単位で設定します。正の値はテクスチャを右に、負の値は左に移動させます。float を書き込みます。
type: docs
weight: 287
url: /ja/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) メソッド


テクスチャの水平オフセットを、シェイプの原点からポイント単位で設定します。正の値はテクスチャを右に、負の値は左に移動させます。**float** を指定します。

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプの画像塗りつぶし形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 画像塗りつぶしモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの水平オフセットを20ポイントに設定します
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 関連項目

* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)