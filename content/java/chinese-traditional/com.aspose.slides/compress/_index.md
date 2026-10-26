---
title: Compress
second_title: Aspose.Slides for Java API 參考
description: 表示一組旨在壓縮的 方法。
type: docs
url: /zh-hant/com.aspose.slides/compress/
---
**繼承：**
java.lang.Object
```
public class Compress
```

表示一組旨在壓縮 [Presentation](../../com.aspose.slides/presentation) 的方法。

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
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [Compress()](#Compress--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Makes compression of the [Presentation](../../com.aspose.slides/presentation) by removing unused master slides. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Makes compression of the [Presentation](../../com.aspose.slides/presentation) by removing unused layout slides. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Makes compression of the [Presentation](../../com.aspose.slides/presentation) by removing unused characters from embedded fonts. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


透過移除未使用的母片，對 [Presentation](../../com.aspose.slides/presentation) 進行壓縮。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 簡報實例 |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


透過移除未使用的版面配置投影片，對 [Presentation](../../com.aspose.slides/presentation) 進行壓縮。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 簡報實例 |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


透過從嵌入式字型中移除未使用的字元，對 [Presentation](../../com.aspose.slides/presentation) 進行壓縮。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 簡報實例 |