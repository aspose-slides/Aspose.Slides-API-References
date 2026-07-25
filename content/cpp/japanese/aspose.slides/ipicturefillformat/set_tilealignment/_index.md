---
title: set_TileAlignment()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャがシェイプ内でどのように配置されるかを設定します。この設定はテクスチャパターンの開始点と、シェイプ全体での繰り返し方法を制御します。RectangleAlignment を指定します。
type: docs
weight: 391
url: /ja/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) method

テクスチャがシェイプ内でどのように配置されるかを設定します。この設定はテクスチャパターンの開始点と、シェイプ全体での繰り返し方法を制御します。[RectangleAlignment](../../rectanglealignment/)を書き込みます。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## 備考

デフォルトは[RectangleAlignment::TopLeft](../../rectanglealignment/)です。

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプのピクチャーフィル形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャーフィルモードを Tile に設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// タイル配置のアラインメントを右下に設定します
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## 参照

* Enum [RectangleAlignment](../../rectanglealignment/)
* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)