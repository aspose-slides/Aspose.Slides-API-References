---
title: set_TileOffsetY()
second_title: Aspose.Slides の C++ API リファレンス
description: テクスチャの垂直方向のオフセットを、シェイプの原点からポイント単位で設定します。正の値はテクスチャを下に移動させ、負の値は上に移動させます。float を書き込みます。
type: docs
weight: 313
url: /ja/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) メソッド

テクスチャの垂直方向のオフセットを、シェイプの原点からポイント単位で設定します。正の値はテクスチャを下方向に移動させ、負の値は上方向に移動させます。**float** を書き込みます。

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## 備考


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプの画像塗りつぶし形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 画像塗りつぶしモードを Tile に設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの垂直オフセットを -50 ポイントに設定します
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## 参照

* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)