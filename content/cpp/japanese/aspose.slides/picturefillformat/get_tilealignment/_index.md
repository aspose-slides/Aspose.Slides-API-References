---
title: get_TileAlignment()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャがシェイプ内でどのように配置されるかを返します。この設定はテクスチャパターンの開始点と、シェイプ全体での繰り返し方法を制御します。RectangleAlignment を参照してください。
type: docs
weight: 378
url: /ja/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() メソッド


テクスチャがシェイプ内でどのように配置されるかを返します。この設定はテクスチャパターンの開始点と、シェイプ全体での繰り返し方法を制御します。参照してください [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## 備考


デフォルトは [RectangleAlignment::TopLeft](../../rectanglealignment/) です。

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプのピクチャーフィル形式を取得
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャーフィルモードをタイルに設定
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// タイル配置のアラインメントを右下に設定
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## 参照

* 列挙型 [RectangleAlignment](../../rectanglealignment/)
* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)