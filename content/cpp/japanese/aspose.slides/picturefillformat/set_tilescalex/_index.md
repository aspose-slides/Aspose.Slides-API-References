---
title: set_TileScaleX()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャ塗りつぶしの水平スケールをパーセンテージで設定します。float を記述します。
type: docs
weight: 339
url: /ja/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) メソッド


テクスチャ塗りつぶしの水平スケールをパーセンテージで設定します。**float** を記述します。

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプのピクチャーフィル形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャーフィルモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの水平スケールを120パーセントに設定します
pictureFillFormat->set_TileScaleX(120.0f);
```

## 参照

* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)