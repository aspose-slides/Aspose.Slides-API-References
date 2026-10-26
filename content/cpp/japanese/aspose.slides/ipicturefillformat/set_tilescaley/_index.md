---
title: set_TileScaleY()
second_title: Aspose.Slides の C++ API リファレンス
description: テクスチャ塗りつぶしの垂直スケールをパーセンテージで設定します。float を記述します。
type: docs
weight: 365
url: /ja/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) メソッド


テクスチャ塗りつぶしの垂直スケールをパーセンテージで設定します。**float** を記述します。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 形状の画像塗りつぶしフォーマットを取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 画像塗りつぶしモードを Tile に設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの垂直スケールを 120 パーセントに設定します
pictureFillFormat->set_TileScaleY(120.0f);
```

## 関連項目

* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)