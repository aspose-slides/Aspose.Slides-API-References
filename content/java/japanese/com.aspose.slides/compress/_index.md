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

[Presentation](../../com.aspose.slides/presentation) を圧縮することを目的としたメソッドのグループを表します。

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
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Compress()](#Compress--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | 未使用のマスタースライドを削除することにより、[Presentation](../../com.aspose.slides/presentation) の圧縮を行います。 |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | 未使用のレイアウトスライドを削除することにより、[Presentation](../../com.aspose.slides/presentation) の圧縮を行います。 |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | 埋め込みフォントから未使用の文字を削除することにより、[Presentation](../../com.aspose.slides/presentation) の圧縮を行います。 |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


未使用のマスタースライドを削除することにより、[Presentation](../../com.aspose.slides/presentation) の圧縮を行います。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | プレゼンテーション インスタンス |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


未使用のレイアウトスライドを削除することにより、[Presentation](../../com.aspose.slides/presentation) の圧縮を行います。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | プレゼンテーション インスタンス |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


埋め込みフォントから未使用の文字を削除することにより、[Presentation](../../com.aspose.slides/presentation) の圧縮を行います。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | プレゼンテーション インスタンス |