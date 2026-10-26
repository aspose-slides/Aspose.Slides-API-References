---
title: ImageFlags
second_title: Aspose.Slides for C++ API リファレンス
description: Image オブジェクトで表されるピクセルデータの属性を表します。
type: docs
weight: 274
url: /ja/system.drawing.imaging/imageflags/
---
## ImageFlags 列挙体


[Image](../../system.drawing/image/) オブジェクトで表されるピクセルデータの属性を表します。

```cpp
enum class ImageFlags
```

### Values

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | スケーラブル。 |
| HasAlpha | 2 | アルファ情報を含みます。 |
| HasTranslucent | 4 | アルファ値が 0 より大きく 255 より小さいものがあります。 |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | ピクセルデータは RGB カラースペースで表現されます。 |
| ColorSpaceCmyk | 32 | ピクセルデータは CMYK カラースペースで表現されます。 |
| ColorSpaceGray | 64 | ピクセルデータはグレースケールです。 |
| ColorSpaceYcbcr | 128 | ピクセルデータは YCBCR カラースペースで表現されます。 |
| ColorSpaceYcck | 256 | ピクセルデータは YCCK カラースペースで表現されます。 |
| HasRealDpi | 4096 | DPI 情報が画像に保存されています。 |
| HasRealPixelSize | 8192 | ピクセルのサイズが画像に保存されています。 |
| ReadOnly | 65536 | ピクセルデータは読み取り専用です。 |
| Caching | 131072 | 高速アクセスのためにキャッシュ可能です。 |

## 参照

* 名前空間 [System::Drawing::Imaging](../)
* ライブラリ [Aspose.Slides](../../)