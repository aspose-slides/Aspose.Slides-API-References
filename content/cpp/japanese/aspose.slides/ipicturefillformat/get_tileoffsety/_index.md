---
title: get_TileOffsetY()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャの垂直オフセット（シェイプの原点からポイント単位）を返します。正の値はテクスチャを下方向に移動させ、負の値は上方向に移動させます。float を読み取ります。
type: docs
weight: 300
url: /ja/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() メソッド


テクスチャの垂直オフセット（シェイプの原点からポイント単位）を返します。正の値はテクスチャを下方向に移動させ、負の値は上方向に移動させます。読み取り **float**。

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## 備考


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプの画像塗りつぶしフォーマットを取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 画像塗りつぶしモードを Tile に設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの垂直オフセットを -50 ポイントに設定します
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## 参照

* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)