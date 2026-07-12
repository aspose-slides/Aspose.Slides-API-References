---
title: Compress
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
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
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) の未使用マスタースライドを削除して圧縮します。 |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) の未使用レイアウトスライドを削除して圧縮します。 |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation) の埋め込みフォントから未使用文字を削除して圧縮します。 |
### Compress() {#Compress--}
```
public Compress()
```

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) の未使用マスタースライドを削除して圧縮します。

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
| pres | [Presentation](../../com.aspose.slides/presentation) | プレゼンテーション インスタンス |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) の未使用レイアウトスライドを削除して圧縮します。

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
| pres | [Presentation](../../com.aspose.slides/presentation) | プレゼンテーション インスタンス |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation) の埋め込みフォントから未使用文字を削除して圧縮します。

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
| pres | [Presentation](../../com.aspose.slides/presentation) | プレゼンテーション インスタンス |