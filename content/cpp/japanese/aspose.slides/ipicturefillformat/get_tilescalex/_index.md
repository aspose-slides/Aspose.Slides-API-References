---
title: get_TileScaleX()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャ塗りつぶしの水平方向のスケールをパーセンテージで返します。読み取り float.
type: docs
weight: 326
url: /ja/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() メソッド

テクスチャの塗りつぶしの水平方向のスケールをパーセンテージで返します。読み取り **float**。

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## 備考


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプの画像塗りつぶしフォーマットを取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 画像塗りつぶしモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの水平方向スケールを120パーセントに設定します
pictureFillFormat->set_TileScaleX(120.0f);
```

## 参照

* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)