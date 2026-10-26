---
title: TiffOptions
second_title: Aspose.Slides for Android 之 Java API 參考
description: 提供控制簡報以 TIFF 格式儲存方式的選項。
type: docs
url: /zh-hant/com.aspose.slides/tiffoptions/
---
**繼承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**已實作的所有介面：**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

提供控制簡報以 TIFF 格式儲存方式的選項。

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // 建立代表簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // 將簡報儲存為 TIFF 文件
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // 建立代表簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // 建立 TiffOptions 類別
>      TiffOptions opts = new TiffOptions();
>      // 設定壓縮類型
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // 壓縮類型
>      // Default - 指定預設的壓縮方案 (LZW)。
>      // None - 表示不使用壓縮。
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // 深度取決於壓縮類型，無法手動設定。
>      // 解析度單位恆為 2（每英吋點數）
>      // 設定圖像 DPI
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // 設定圖像大小
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // 使用指定的圖像大小將簡報儲存為 TIFF
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // 建立代表簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat 包含以下值（如文件中所示）：
>      //Format1bppIndexed; // 1 位元每像素，已索引。
>      //Format4bppIndexed; // 4 位元每像素，已索引。
>      //Format8bppIndexed; // 8 位元每像素，已索引。
>      //Format24bppRgb; // 24 位元每像素，RGB。
>      //Format32bppArgb; // 32 位元每像素，ARGB。
> 
>      // 使用指定的圖像大小將簡報儲存為 TIFF
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 建構函式

| 建構子 | 描述 |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | 預設建構函式。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | 提供控制匯出文件中 Ink 物件外觀的選項。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否應包含隱藏投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否應包含隱藏投影片。 |
| [getImageSize()](#getImageSize--) | 指定產生的 TIFF 圖像大小。 |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | 指定產生的 TIFF 圖像大小。 |
| [getDpiX()](#getDpiX--) | 指定水平解析度（每英吋點數）。 |
| [setDpiX(long value)](#setDpiX-long-) | 指定水平解析度（每英吋點數）。 |
| [getDpiY()](#getDpiY--) | 指定垂直解析度（每英吋點數）。 |
| [setDpiY(long value)](#setDpiY-long-) | 指定垂直解析度（每英吋點數）。 |
| [getCompressionType()](#getCompressionType--) | 指定壓縮類型。 |
| [setCompressionType(int value)](#setCompressionType-int-) | 指定壓縮類型。 |
| [getPixelFormat()](#getPixelFormat--) | 指定產生圖像的像素格式。 |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 指定產生圖像的像素格式。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getBwConversionMode()](#getBwConversionMode--) | 指定將彩色圖像轉換為黑白圖像的演算法。 |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | 指定將彩色圖像轉換為黑白圖像的演算法。 |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

預設建構函式。

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

提供控制匯出文件中 Ink 物件外觀的選項。唯讀 [IInkOptions](../../com.aspose.slides/iinkoptions)

**傳回：**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**傳回：**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```

指定產生的 TIFF 圖像大小。預設值為 0x0，表示產生的圖像尺寸將根據簡報投影片大小計算。讀寫 [Size](../../com.aspose.slides.android/size)。

**傳回：**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```

指定產生的 TIFF 圖像大小。預設值為 0x0，表示產生的圖像尺寸將根據簡報投影片大小計算。讀寫 [Size](../../com.aspose.slides.android/size)。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

指定水平解析度（每英吋點數）。讀寫 long。

**傳回：**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

指定水平解析度（每英吋點數）。讀寫 long。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

指定垂直解析度（每英吋點數）。讀寫 long。

**傳回：**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

指定垂直解析度（每英吋點數）。讀寫 long。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

指定壓縮類型。讀寫 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**傳回：**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

指定壓縮類型。讀寫 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

指定產生圖像的像素格式。讀寫 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**傳回：**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

指定產生圖像的像素格式。讀寫 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

指定將彩色圖像轉換為黑白圖像的演算法。此選項僅在 CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) 設為 [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) 或 [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) 時套用。讀寫 [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)。預設為 [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)。

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
public final void setBwConversionMode(int value)
```

指定將彩色圖像轉換為黑白圖像的演算法。此選項僅在 CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) 設為 [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) 或 [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) 時套用。讀寫 [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)。預設為 [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)。

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
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | int |  |