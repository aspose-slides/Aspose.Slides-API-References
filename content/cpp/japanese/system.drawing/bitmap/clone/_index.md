---
title: Clone()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトのコピーを作成します。
type: docs
weight: 183
url: /ja/system.drawing/bitmap/clone/
---
## Bitmap::Clone() メソッド

現在のオブジェクトのコピーを作成します。

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### 戻り値

現在のオブジェクトのコピー。

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) メソッド

現在のオブジェクトで表されるビットマップ画像の領域のコピーを表す[Bitmap](../)オブジェクトを作成します。

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | コピーする領域を指定する矩形 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 新しい[Bitmap](../)のピクセル形式 |

### 戻り値

作成された[Bitmap](../)オブジェクト

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) メソッド

現在のオブジェクトで表されるビットマップ画像の領域のコピーを表す[Bitmap](../)オブジェクトを作成します。

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | コピーする領域を指定する矩形 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 新しい[Bitmap](../)のピクセル形式 |

### 戻り値

作成された[Bitmap](../)オブジェクト

## 参照

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)