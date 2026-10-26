---
title: DrawImageUnscaled()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された位置に、元の実際サイズを使用して指定された画像を描画します。
type: docs
weight: 443
url: /ja/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) メソッド

指定した位置に、元の実際サイズを使用して指定された画像を描画します。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| x | int | 描画された画像の左上隅の X 座標 |
| y | int | 描画された画像の左上隅の Y 座標 |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) メソッド

指定された位置に、元の実際サイズを使用して指定された画像を描画します。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| x | int | 描画された画像の左上隅の X 座標 |
| y | int | 描画された画像の左上隅の Y 座標 |
| width | int | 使用されません |
| height | int | 使用されません |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) メソッド

指定された位置に、元の実際サイズを使用して指定された画像を描画します。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| rect | const [Rectangle](../../rectangle/)\& | 描画された画像の左上隅を指定する矩形。矩形の X および Y プロパティが左上隅を指定します。幅と高さの値は無視されます。 |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) メソッド

指定された位置に、元の実際サイズを使用して指定された画像を描画します。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 描画する画像 |
| point | const [Point](../../point/)\& | 描画された画像の左上隅を指定する [Point](../../point/) 構造体。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Image](../../image/)
* クラス [Graphics](../)
* クラス [Rectangle](../../rectangle/)
* クラス [Point](../../point/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)