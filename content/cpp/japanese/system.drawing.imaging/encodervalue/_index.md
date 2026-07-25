---
title: EncoderValue
second_title: Aspose.Slides for C++ API リファレンス
description: JPEG または TIFF 画像エンコーダーに渡されるパラメータ値を指定します。
type: docs
weight: 261
url: /ja/system.drawing.imaging/encodervalue/
---
## EncoderValue 列挙体

JPEG または TIFF 画像エンコーダーに渡されるパラメータ値を指定します。

```cpp
enum class EncoderValue
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| ColorTypeCMYK | 0 | CMYK カラースペースです。 |
| ColorTypeYCCK | 1 | YCCK カラースペースです。 |
| CompressionLZW | 2 | LZW 圧縮方式です。 |
| CompressionCCITT3 | 3 | TIFF 画像に対する CCITT3 圧縮方式を指定します。 |
| CompressionCCITT4 | 4 | TIFF 画像に対する CCITT4 圧縮方式を指定します。 |
| CompressionRle | 5 | TIFF 画像に対する RLE 圧縮方式を指定します。 |
| CompressionNone | 6 | TIFF 画像に対して圧縮しないことを指定します。 |
| ScanMethodInterlaced | 7 | インターレースモードです。 |
| ScanMethodNonInterlaced | 8 | 非インターレースモードです。 |
| VersionGif87 | 9 | TIFF 画像に対してバージョン 87 を指定します。 |
| VersionGif89 | 10 | GIF 画像に対してバージョン 89a を指定します。 |
| RenderProgressive | 11 | プログレッシブモードです。 |
| RenderNonProgressive | 12 | 非プログレッシブモードです。 |
| TransformRotate90 | 13 | JPEG 画像に対し、90 度の時計回りロスレス回転を指定します。 |
| TransformRotate180 | 14 | JPEG 画像に対して 180 度のロスレス回転を指定します。 |
| TransformRotate270 | 15 | JPEG 画像に対して 270 度時計回りのロスレス回転を指定します。 |
| TransformFlipHorizontal | 16 | JPEG 画像に対して水平反転のロスレス操作を指定します。 |
| TransformFlipVertical | 17 | JPEG 画像に対して垂直反転のロスレス操作を指定します。 |
| MultiFrame | 18 | マルチフレームエンコーディングです。 |
| LastFrame | 19 | マルチフレーム画像の最後のフレームです。 |
| Flush | 20 | エンコーダーオブジェクトは閉じられます。 |
| FrameDimensionTime | 21 | GIF 画像の時間フレーム次元を指定します。 |
| FrameDimensionResolution | 22 | 解像度フレーム次元です。 |
| FrameDimensionPage | 23 | TIFF 画像のページフレーム次元を指定します。 |

## 参照

* 名前空間 [System::Drawing::Imaging](../)
* ライブラリ [Aspose.Slides](../../)