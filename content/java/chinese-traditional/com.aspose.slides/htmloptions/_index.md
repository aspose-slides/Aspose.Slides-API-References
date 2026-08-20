---
title: HtmlOptions
second_title: Aspose.Slides for Java API 參考文件
description: 表示 HTML 匯出選項。
type: docs
url: /zh-hant/com.aspose.slides/htmloptions/
---
**繼承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**已實作的介面：**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

表示 HTML 匯出選項。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | 建立一個新的 HtmlOptions 物件以指定回呼。 |
| [HtmlOptions()](#HtmlOptions--) | 建立一個新的 HtmlOptions 物件，用於儲存為單一 HTML 檔案。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 取得或設定在匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時投影片在頁面上的放置模式。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 取得或設定在匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時投影片在頁面上的放置模式。 |
| [getInkOptions()](#getInkOptions--) | 提供控制匯出文件中 Ink 物件外觀的選項。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否應包含隱藏投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否應包含隱藏投影片。 |
| [getHtmlFormatter()](#getHtmlFormatter--) | 取得或設定 HTML 範本。 |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | 取得或設定 HTML 範本。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 取得或設定指示文字是否在不使用連字的情況下呈現的值。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 取得或設定指示文字是否在不使用連字的情況下呈現的值。 |
| [getSlideImageFormat()](#getSlideImageFormat--) | 取得或設定投影片影像格式選項。 |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | 取得或設定投影片影像格式選項。 |
| [getJpegQuality()](#getJpegQuality--) | 取得或設定決定 PDF 文件內 JPEG 圖像品質的值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 取得或設定決定 PDF 文件內 JPEG 圖像品質的值。 |
| [getPicturesCompression()](#getPicturesCompression--) | 表示圖片壓縮等級 |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 表示圖片壓縮等級 |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 布林旗標，指出裁切部分是否保留在文件中。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 布林旗標，指出裁切部分是否保留在文件中。 |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | 設定為 true 可從 svg 容器中排除寬度與高度屬性——這將使版面配置具有彈性。 |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | 設定為 true 可從 svg 容器中排除寬度與高度屬性——這將使版面配置具有彈性。 |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

建立一個新的 HtmlOptions 物件以指定回呼。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | 用於控制儲存專案的回呼物件。 |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

建立一個新的 HtmlOptions 物件，用於儲存為單一 HTML 檔案。

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

取得或設定在匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時投影片在頁面上的放置模式。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回值：**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

取得或設定在匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時投影片在頁面上的放置模式。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

提供控制匯出文件中 Ink 物件外觀的選項。唯讀 [IInkOptions](../../com.aspose.slides/iinkoptions)

**傳回值：**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**傳回值：**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

取得或設定 HTML 範本。可讀寫 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**傳回值：**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

取得或設定 HTML 範本。可讀寫 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

取得或設定指示文字是否在不使用連字的情況下呈現的值。設定為 true 時，連字將在輸出中被停用。預設情況下，此屬性設定為 false。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回值：**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

取得或設定指示文字是否在不使用連字的情況下呈現的值。設定為 true 時，連字將在輸出中被停用。預設情況下，此屬性設定為 false。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

取得或設定投影片影像格式選項。可讀寫 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**傳回值：**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

取得或設定投影片影像格式選項。可讀寫 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

取得或設定決定 PDF 文件內 JPEG 圖像品質的值。可讀寫 byte。

--------------------

僅在文件包含 JPEG 圖像時才會生效。

使用此屬性可在以 PDF 格式儲存文件時取得或設定文件內圖像的品質。值的範圍為 0 到 100，0 代表最差品質且壓縮率最高，100 代表最佳品質且壓縮率最低。

預設值為 **95**。

**傳回值：**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

取得或設定決定 PDF 文件內 JPEG 圖像品質的值。可讀寫 byte。

--------------------

僅在文件包含 JPEG 圖像時才會生效。

使用此屬性可在以 PDF 格式儲存文件時取得或設定文件內圖像的品質。值的範圍為 0 到 100，0 代表最差品質且壓縮率最高，100 代表最佳品質且壓縮率最低。

預設值為 **95**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

表示圖片壓縮等級

**傳回值：**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

表示圖片壓縮等級

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

布林旗標，指出裁切部分是否仍保留在文件中。若為 true，裁切部分將被移除；若為 false，則會序列化於文件中（可能導致檔案變大）。

**傳回值：**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

布林旗標，指出裁切部分是否仍保留在文件中。若為 true，裁切部分將被移除；若為 false，則會序列化於文件中（可能導致檔案變大）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

設定為 true 時，會從 svg 容器中排除寬度和高度屬性——這將使版面配置具彈性。設定為 false 時則相反。可讀寫布林值。

**傳回值：**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

設定為 true 時，會從 svg 容器中排除寬度和高度屬性——這將使版面配置具彈性。設定為 false 時則相反。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |