---
title: TextureBrush()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された画像を使用する TextureBrush クラスの新しいインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) コンストラクタ

指定された画像を使用する[TextureBrush](../)クラスの新しいインスタンスを構築します。

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | シェイプの内部を塗りつぶすためにブラシが使用する画像 |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | ブラシオブジェクトのタイル化方法を指定します |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) コンストラクタ

指定された画像を使用する[TextureBrush](../)クラスの新しいインスタンスを構築します。

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | シェイプの内部を塗りつぶすためにブラシが使用する画像 |
| dst_rect | [RectangleF](../../rectanglef/) | ブラシのバウンディング矩形を指定します |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | 画像属性 |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) コンストラクタ

指定された画像を使用する[TextureBrush](../)クラスの新しいインスタンスを構築します。

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | シェイプの内部を塗りつぶすためにブラシが使用する画像 |
| dst_rect | [Rectangle](../../rectangle/) | ブラシのバウンディング矩形を指定します |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | 画像属性 |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) コンストラクタ

指定された画像を使用する[TextureBrush](../)クラスの新しいインスタンスを構築します。

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | シェイプの内部を塗りつぶすためにブラシが使用する画像 |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | ブラシオブジェクトのタイル化方法を指定します |
| dst_rect | [RectangleF](../../rectanglef/) | ブラシのバウンディング矩形を指定します |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) コンストラクタ

指定された画像を使用する[TextureBrush](../)クラスの新しいインスタンスを構築します。

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | シェイプの内部を塗りつぶすためにブラシが使用する画像 |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | ブラシオブジェクトのタイル化方法を指定します |
| dst_rect | [Rectangle](../../rectangle/) | ブラシのバウンディング矩形を指定します |

## 参照

* 列挙型 [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Image](../../image/)
* クラス [TextureBrush](../)
* クラス [RectangleF](../../rectanglef/)
* クラス [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* クラス [Rectangle](../../rectangle/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)