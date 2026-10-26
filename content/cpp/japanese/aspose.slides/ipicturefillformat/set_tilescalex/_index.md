---
title: set_TileScaleX()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャ塗りつぶしの水平スケールをパーセンテージで設定します。floatで記述します。
type: docs
weight: 339
url: /ja/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) メソッド

テクスチャ塗りつぶしの水平スケールをパーセンテージで設定します。**float** で書き込みます。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## 備考

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプの画像塗りつぼしフォーマットを取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 画像塗りつぼしモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの水平スケールを120パーセントに設定します
pictureFillFormat->set_TileScaleX(120.0f);
```

## 関連項目

* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)