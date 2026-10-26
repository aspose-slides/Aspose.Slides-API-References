---
title: get_TileFlip()
second_title: Aspose.Slides for C++ API リファレンス
description: "テクスチャ タイルを水平方向、垂直方向、またはその両方の軸で反転させます。Slides::TileFlip を参照してください。"
type: docs
weight: 404
url: /ja/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() メソッド


テクスチャ タイルを水平方向、垂直方向、またはその両方の軸で反転させます。参照 [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## 備考


デフォルトは [TileFlip::NoFlip](../../tileflip/)。 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプの画像塗りつぶし形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 画像塗りつぶしモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャ タイルを垂直軸で反転させます。
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## 参照

* Enum [TileFlip](../../tileflip/)
* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)