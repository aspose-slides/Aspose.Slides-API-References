---
title: get_TileFlip()
second_title: Aspose.Slides for C++ API リファレンス
description: "テクスチャ タイルを水平、垂直、または両方の軸周りに反転させます。Slides::TileFlip を参照してください。"
type: docs
weight: 404
url: /ja/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() メソッド

テクスチャ タイルを水平、垂直、または両方の軸周りに反転させます。参照 [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## 備考

デフォルトは [TileFlip::NoFlip](../../tileflip/) です。

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプのピクチャーフィル形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャーフィルモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャ タイルを垂直軸周りに反転させます
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## 参照

* 列挙体 [TileFlip](../../tileflip/)
* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)