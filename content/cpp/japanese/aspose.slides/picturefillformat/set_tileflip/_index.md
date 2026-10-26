---
title: set_TileFlip()
second_title: Aspose.Slides for C++ API リファレンス
description: "テクスチャ タイルを水平、垂直、または両方の軸周りに反転させます。Slides::TileFlip を記述します。"
type: docs
weight: 417
url: /ja/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) メソッド


テクスチャ タイルを水平、垂直、または両方の軸回りに反転させます。[Slides::TileFlip](../../tileflip/)を書き込みます。

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## 備考


デフォルトは[TileFlip::NoFlip](../../tileflip/)です。 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプのピクチャーフィル形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャーフィルモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャタイルを垂直軸周りに反転させます
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## 関連項目

* 列挙体 [TileFlip](../../tileflip/)
* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)