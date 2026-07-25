---
title: get_TileScaleX()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャの塗りつぶしの水平スケールをパーセンテージで返します。float を読み取ります。
type: docs
weight: 326
url: /ja/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() メソッド


テクスチャの塗りつぶしの水平スケールをパーセンテージで返します。読み取り **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 図形のピクチャ塗りつぶし形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャ塗りつぶしモードを Tile に設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの水平スケールを 120 パーセントに設定します
pictureFillFormat->set_TileScaleX(120.0f);
```

## 参照

* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)