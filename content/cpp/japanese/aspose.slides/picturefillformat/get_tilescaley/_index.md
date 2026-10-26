---
title: get_TileScaleY()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャ塗りつぶしの垂直スケールをパーセンテージで返します。float を読み取ります。
type: docs
weight: 352
url: /ja/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() メソッド

Returns the vertical scale for the texture fill as a percentage. Read **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## 備考


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプのピクチャーフィル形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャーフィルモードを Tile に設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの垂直スケールを 120 パーセントに設定します
pictureFillFormat->set_TileScaleY(120.0f);
```

## 参照

* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)