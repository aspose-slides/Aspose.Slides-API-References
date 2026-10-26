---
title: get_TileScaleY()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャ塗りつぶしの垂直スケールをパーセンテージで返します。読み取り float.
type: docs
weight: 352
url: /ja/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() メソッド


テクスチャの塗りつぶしの垂直スケールをパーセンテージで返します。読み取り **float**。

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプの画像塗りつぶし形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 画像塗りつぶしモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの垂直スケールを120パーセントに設定します
pictureFillFormat->set_TileScaleY(120.0f);
```

## 参照

* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)