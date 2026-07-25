---
title: set_TileOffsetX()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャの水平オフセットをシェイプの原点からポイント単位で設定します。正の値はテクスチャを右方向に移動させ、負の値は左方向に移動させます。float を記述します。
type: docs
weight: 287
url: /ja/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) メソッド


テクスチャの水平オフセットをシェイプの原点からポイント単位で設定します。正の値はテクスチャを右方向に移動させ、負の値は左方向に移動させます。**float** を記述します。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプのピクチャーフィルフォーマットを取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャーフィルモードを Tile に設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// テクスチャの水平オフセットを 20 ポイントに設定します
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 参照

* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)