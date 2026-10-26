---
title: get_TileAlignment()
second_title: Aspose.Slides for C++ API リファレンス
description: テクスチャがシェイプ内でどのように配置されるかを返します。この設定はテクスチャパターンの開始点とシェイプ全体での繰り返し方法を制御します。RectangleAlignment を参照してください。
type: docs
weight: 378
url: /ja/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() メソッド


テクスチャがシェイプ内でどのように配置されるかを返します。この設定はテクスチャパターンの開始点とシェイプ全体での繰り返し方法を制御します。[RectangleAlignment](../../rectanglealignment/) を参照してください。

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## 備考


デフォルトは [RectangleAlignment::TopLeft](../../rectanglealignment/) です。 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// シェイプの画像塗りつぶし形式を取得します
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 画像塗りつぶしモードを Tile に設定します
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// タイル配置の整列を右下に設定します
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## 参照

* 列挙型 [RectangleAlignment](../../rectanglealignment/)
* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)