---
title: set_TileAlignment()
second_title: Aspose.Slides for C++ API リファレンス
description: シェイプ内でテクスチャがどのように配置されるかを設定します。この設定はテクスチャ パターンの開始点と、シェイプ全体での繰り返し方法を制御します。RectangleAlignment を書き込みます。
type: docs
weight: 391
url: /ja/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) メソッド

シェイプ内でテクスチャがどのように配置されるかを設定します。この設定はテクスチャ パターンの開始点と、シェイプ全体での繰り返し方法を制御します。[RectangleAlignment](../../rectanglealignment/)を書き込みます。

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## 備考

デフォルトは [RectangleAlignment::TopLeft](../../rectanglealignment/) です。 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプのピクチャーフィル形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// ピクチャーフィルモードをタイルに設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// タイルの配置を右下に設定します
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## 参照

* 列挙型 [RectangleAlignment](../../rectanglealignment/)
* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)