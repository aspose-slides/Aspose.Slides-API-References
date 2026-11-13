---
title: Compress
second_title: Aspose.Slides for Java API 參考說明
description: 代表一組旨在壓縮 的方法。
type: docs
url: /zh-hant/com.aspose.slides/compress/
---
**繼承：**
java.lang.Object
```
public class Compress
```

代表一組用於壓縮 [Presentation](../../com.aspose.slides/presentation) 的方法。

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
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [Compress()](#Compress--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | 透過套用所有可用的壓縮步驟來減小簡報的大小：

 *  移除未使用的母版投影片 \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  移除未使用的版面配置投影片 \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  僅保留嵌入字型中實際使用的字形 \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  將圖片解析度降低至 150 DPI，並刪除圖片的裁剪區域 \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | 透過移除未使用的母版投影片來壓縮 [Presentation](../../com.aspose.slides/presentation)。 |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | 透過移除未使用的版面配置投影片來壓縮 [Presentation](../../com.aspose.slides/presentation)。 |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | 透過從嵌入字型中移除未使用的字元來壓縮 [Presentation](../../com.aspose.slides/presentation)。 |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | 降低簡報中圖片的解析度並刪除其裁剪區域，類似於 PowerPoint 所有圖片的「壓縮圖片」功能。 |

### Compress() {#Compress--}
```
public Compress()
```

### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```

透過套用所有可用的壓縮步驟來減小簡報的大小：

 *  移除未使用的母版投影片 \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  移除未使用的版面配置投影片 \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  僅保留嵌入字型中實際使用的字形 \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  將圖片解析度降低至 150 DPI，並刪除圖片的裁剪區域 \#compressImages(IPresentation,int).compressImages(IPresentation,int).

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | 要壓縮的簡報。 |

若要自訂壓縮，例如使用不同的圖片解析度或跳過某個步驟，請改為個別呼叫上列的方法，而非使用此方法。圖片的裁剪區域會永久移除，且無法在 PowerPoint 中還原。 |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

透過移除未使用的母版投影片來壓縮 [Presentation](../../com.aspose.slides/presentation)。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 簡報實例 |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

透過移除未使用的版面配置投影片來壓縮 [Presentation](../../com.aspose.slides/presentation)。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 簡報實例 |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

透過從嵌入字型中移除未使用的字元來壓縮 [Presentation](../../com.aspose.slides/presentation)。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 簡報實例 |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```

降低簡報中圖片的解析度並刪除其裁剪區域，類似於 PowerPoint 所有圖片的「壓縮圖片」功能。會處理投影片、版面配置投影片和母版投影片上的圖片，包括群組圖形內的圖片以及圖形的圖片填充。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 要處理的簡報。 |
| resolution | int | 相對於每張圖片顯示大小的目標解析度。[PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) 會保留圖片不變。

已達或低於目標解析度的圖片將保持不變；圖片永不會被放大。

不會處理的項目：投影片背景、表格儲存格填滿、圖表、SmartArt、GIF 圖片（以保留動畫）、SVG 與中繪圖（EMF/WMF）圖片。

裁剪區域會永久移除，且無法在 PowerPoint 中還原。 |