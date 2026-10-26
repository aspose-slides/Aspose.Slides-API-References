---
title: set_TileScaleY()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャ塗りつぶしの垂直スケールをパーセンテージで設定します。float を書き込みます。
type: docs
weight: 365
url: /ja/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) メソッド

テクスチャ塗りつぶしの垂直スケールをパーセンテージで設定します。**float** を書き込みます。

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## 備考

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 形状のピクチャー塗りつぶし形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャー塗りつぶしモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの垂直スケールを120％に設定します
pictureFillFormat->set_TileScaleY(120.0f);
```

## 参照

* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)