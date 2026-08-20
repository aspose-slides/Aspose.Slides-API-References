---
title: ITiffOptions
second_title: Aspose.Slides for Java API 參考
description: 提供控制簡報以 TIFF 格式儲存之選項。
type: docs
url: /zh-hant/com.aspose.slides/itiffoptions/
---
**已實作的介面：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

提供控制簡報以 TIFF 格式儲存之選項。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getImageSize()](#getImageSize--) | 指定產生的 TIFF 影像的大小。 |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | 指定產生的 TIFF 影像的大小。 |
| [getDpiX()](#getDpiX--) | 指定水平解析度（每英吋點數）。 |
| [setDpiX(long value)](#setDpiX-long-) | 指定水平解析度（每英吋點數）。 |
| [getDpiY()](#getDpiY--) | 指定垂直解析度（每英吋點數）。 |
| [setDpiY(long value)](#setDpiY-long-) | 指定垂直解析度（每英吋點數）。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否應包含隱藏投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否應包含隱藏投影片。 |
| [getCompressionType()](#getCompressionType--) | 指定壓縮類型。 |
| [setCompressionType(int value)](#setCompressionType-int-) | 指定壓縮類型。 |
| [getPixelFormat()](#getPixelFormat--) | 指定產生影像的像素格式。 |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 指定產生影像的像素格式。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 取得或設定匯出簡報時投影片在頁面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 取得或設定匯出簡報時投影片在頁面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getBwConversionMode()](#getBwConversionMode--) | 指定將彩色影像轉換為黑白影像的演算法。 |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | 指定將彩色影像轉換為黑白影像的演算法。 |
| [getInkOptions()](#getInkOptions--) | 提供控制匯出文件中 Ink 物件外觀的選項。 |
### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```

指定產生的 TIFF 影像的大小。預設值為 0x0，表示將根據簡報投影片尺寸值計算產生的影像大小。Read/write java.awt.Dimension.

**傳回：**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```

指定產生的 TIFF 影像的大小。預設值為 0x0，表示將根據簡報投影片尺寸值計算產生的影像大小。Read/write java.awt.Dimension。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

指定水平解析度（每英吋點數）。Read/write long.

**傳回：**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

指定水平解析度（每英吋點數）。Read/write long.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

指定垂直解析度（每英吋點數）。Read/write long.

**傳回：**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

指定垂直解析度（每英吋點數）。Read/write long.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定產生的文件是否應包含隱藏投影片。預設值為 false。

**傳回：**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定產生的文件是否應包含隱藏投影片。預設值為 false。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

指定壓縮類型。Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**傳回：**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

指定壓縮類型。Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

指定產生影像的像素格式。Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**傳回：**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

指定產生影像的像素格式。Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

取得或設定匯出簡報時投影片在頁面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回：**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

取得或設定匯出簡報時投影片在頁面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

指定將彩色影像轉換為黑白影像的演算法。此選項僅在 CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) 設為 [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) 或 [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) 時套用。Read/write [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)。預設值為 [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)。

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回：**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

指定將彩色影像轉換為黑白影像的演算法。此選項僅在 CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) 設為 [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) 或 [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) 時套用。Read/write [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)。預設值為 [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)。

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

提供控制匯出文件中 Ink 物件外觀的選項。Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**傳回：**
[IInkOptions](../../com.aspose.slides/iinkoptions)