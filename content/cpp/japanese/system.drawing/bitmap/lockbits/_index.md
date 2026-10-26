---
title: LockBits()
second_title: Aspose.Slides の C++ API リファレンス
description: Bitmap をシステムメモリにロックします。
type: docs
weight: 118
url: /ja/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) メソッド


[Bitmap](../) をシステムメモリにロックします。

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | ロックする画像領域を指定する矩形 |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | ビットマップへのアクセスレベルを指定 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | このビットマップのデータ形式 |

### 戻り値

ロック操作の情報を含む BitmapData オブジェクトへの共有ポインタ

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) メソッド


[Bitmap](../) をシステムメモリにロックします。

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | ロックする画像領域を指定する矩形 |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | ビットマップへのアクセスレベルを指定 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | このビットマップのデータ形式 |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | ロック操作に関する情報を含む |

### 戻り値

ロック操作の情報を含む BitmapData オブジェクトへの共有ポインタ

## 参照

* 列挙型 [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* 列挙型 [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* 型定義 [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* クラス [Rectangle](../../rectangle/)
* クラス [Bitmap](../)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)