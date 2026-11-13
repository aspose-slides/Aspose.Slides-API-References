---
title: Compress
second_title: Aspose.Slides for Java API リファレンス
description: 圧縮を目的としたメソッドのグループを表します。
type: docs
url: /ja/com.aspose.slides/compress/
---
**継承:**
java.lang.Object
```
public class Compress
```

圧縮を目的としたメソッドのグループを表します [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Compress()](#Compress--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | 利用可能なすべての圧縮手順を適用してプレゼンテーションのサイズを縮小します：

 *  未使用のマスタースライドを削除します \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  未使用のレイアウトスライドを削除します \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  埋め込みフォントで実際に使用されているグリフのみを保持します \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  画像の解像度を150 DPIに下げ、画像の切り取り領域を削除します \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | 未使用のマスタースライドを削除することで [Presentation](../../com.aspose.slides/presentation) の圧縮を行います。 |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | 未使用のレイアウトスライドを削除することで [Presentation](../../com.aspose.slides/presentation) の圧縮を行います。 |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | 埋め込みフォントから未使用の文字を削除することで [Presentation](../../com.aspose.slides/presentation) の圧縮を行います。 |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | プレゼンテーション内の画像の解像度を下げ、切り取り領域を削除します。これは PowerPoint の「画像の圧縮」をすべての画像に適用したものに相当します。 |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


利用可能なすべての圧縮手順を適用してプレゼンテーションのサイズを縮小します：

 *  未使用のマスタースライドを削除します \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  未使用のレイアウトスライドを削除します \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  埋め込みフォントで実際に使用されているグリフのみを保持します \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  画像の解像度を150 DPIに下げ、画像の切り取り領域を削除します \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | 圧縮対象のプレゼンテーション。 |

--------------------

圧縮をカスタマイズするには、たとえば異なる画像解像度を使用したり手順をスキップしたりする場合、上記のメソッドを個別に呼び出してください。このメソッドを使用しないでください。画像の切り取り領域は永久に削除され、PowerPoint では復元できません。 |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


[Presentation](../../com.aspose.slides/presentation) の圧縮を、未使用のマスタースライドを削除することで行います。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | プレゼンテーション インスタンス。 |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


[Presentation](../../com.aspose.slides/presentation) の圧縮を、未使用のレイアウトスライドを削除することで行います。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | プレゼンテーション インスタンス。 |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


[Presentation](../../com.aspose.slides/presentation) の圧縮を、埋め込みフォントから未使用の文字を削除することで行います。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | プレゼンテーション インスタンス。 |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


プレゼンテーション内の画像の解像度を下げ、切り取り領域を削除します。これは PowerPoint の「画像の圧縮」をすべての画像に適用したものに相当します。スライド、レイアウトスライド、マスタースライド上の画像が処理され、グループシェイプ内やシェイプの画像塗りつぶしの画像も含まれます。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressImages(pres, PicturesCompression.Dpi150);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 処理対象のプレゼンテーション。 |
| resolution | int | 各画像が表示されるサイズに対する目標解像度。[PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) は画像を変更しません。 |

目標解像度以下または同じ解像度の画像は変更されません。画像は決して拡大されません。

処理対象外: スライドの背景、テーブルセルの塗りつぶし、チャート、SmartArt、GIF 画像（アニメーションを保持するため）、SVG およびメタファイル（EMF/WMF）画像。

切り取り領域は永久に削除され、PowerPoint では復元できません。 |