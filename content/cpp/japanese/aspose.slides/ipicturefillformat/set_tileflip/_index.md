---
title: set_TileFlip()
second_title: Aspose.Slides for C++ API リファレンス
description: "テクスチャ タイルを水平、垂直、またはその両方の軸を中心に反転させます。Slides::TileFlipを書き込みます。"
type: docs
weight: 417
url: /ja/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) メソッド

テクスチャ タイルを水平、垂直、またはその両方の軸を中心に反転させます。[Slides::TileFlip](../../tileflip/)を書き込みます。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## 備考

デフォルトは [TileFlip::NoFlip](../../tileflip/) です。

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプの画像塗りつぶしフォーマットを取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 画像塗りつぶしモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャタイルを垂直軸に沿って反転させます。
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## 参照

* 列挙型 [TileFlip](../../tileflip/)
* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)