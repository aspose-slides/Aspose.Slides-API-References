---
title: SlideImageFormat
second_title: Aspose.Slides for Android via Java API リファレンス
description: HTML エクスポート用のプレゼンテーションでスライド画像が保存される形式を決定します。
type: docs
url: /ja/com.aspose.slides/slideimageformat/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)  
```
public class SlideImageFormat implements ISlideImageFormat
```

スライド画像が HTML エクスポート用に保存される形式を決定します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | スライドは SVG 形式に変換される必要があります。 |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | スライドはラスタ画像に変換される必要があります。 |

### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

スライドは SVG 形式に変換される必要があります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | SVG エクスポートのオプション。 |

**戻り値:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - [SlideImageFormat](../../com.aspose.slides/slideimageformat) オブジェクト。

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

スライドはラスタ画像に変換される必要があります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scale | float | 出力画像を拡大縮小する係数。 |
| imageFormat | int | 結果画像の形式（例: PNG、JPEG）。 |

**戻り値:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -