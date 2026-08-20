---
title: IHtmlOptions
second_title: Aspose.Slides for Java API 參考
description: 代表 HTML 匯出選項。
type: docs
url: /zh-hant/com.aspose.slides/ihtmloptions/
---
**已實作的所有介面：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

代表 HTML 匯出選項。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | 返回或設定 HTML 範本。 |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | 返回或設定 HTML 範本。 |
| [getSlideImageFormat()](#getSlideImageFormat--) | 返回或設定投影片影像格式選項。 |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | 返回或設定投影片影像格式選項。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否應包含隱藏投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否應包含隱藏投影片。 |
| [getJpegQuality()](#getJpegQuality--) | 返回或設定 PDF 文件內 JPEG 影像品質的值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 返回或設定 PDF 文件內 JPEG 影像品質的值。 |
| [getPicturesCompression()](#getPicturesCompression--) | 代表圖片壓縮等級 讀寫 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 代表圖片壓縮等級 讀寫 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 布林旗標表示裁切部份是否保留在文件中。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 布林旗標表示裁切部份是否保留在文件中。 |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | 設定為 true 時，從 SVG 容器中排除寬度和高度屬性——這將使版面配置具備回應式。 |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | 設定為 true 時，從 SVG 容器中排除寬度和高度屬性——這將使版面配置具備回應式。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 取得或設定指示文字是否在不使用連字的情況下渲染的值。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 取得或設定指示文字是否在不使用連字的情況下渲染的值。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getInkOptions()](#getInkOptions--) | 提供控制匯出文件中 Ink 物件外觀的選項。 |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

返回或設定 HTML 範本。讀寫 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**傳回：**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

返回或設定 HTML 範本。讀寫 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

返回或設定投影片影像格式選項。讀寫 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**傳回：**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

返回或設定投影片影像格式選項。讀寫 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**傳回：**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

返回或設定 PDF 文件內 JPEG 影像品質的值。讀寫 byte.

--------------------

僅在文件包含 JPEG 影像時才有效。

使用此屬性在儲存為 PDF 格式時取得或設定文件內影像的品質。值範圍為 0 到 100，0 表示最差品質但最高壓縮，100 表示最佳品質但最低壓縮。

預設值為 **95**。

**傳回：**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

返回或設定 PDF 文件內 JPEG 影像品質的值。讀寫 byte.

--------------------

僅在文件包含 JPEG 影像時才有效。

使用此屬性在儲存為 PDF 格式時取得或設定文件內影像的品質。值範圍為 0 到 100，0 表示最差品質但最高壓縮，100 表示最佳品質但最低壓縮。

預設值為 **95**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

代表圖片壓縮等級 讀寫 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))。

**傳回：**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

代表圖片壓縮等級 讀寫 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

布林旗標表示裁切部份是否保留在文件中。若為 true，裁切部份會被移除；若為 false，則會在文件中序列化（可能導致檔案變大） 讀寫 boolean。

**傳回：**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

布林旗標表示裁切部份是否保留在文件中。若為 true，裁切部份會被移除；若為 false，則會在文件中序列化（可能導致檔案變大） 讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

設定為 true 時，從 SVG 容器中排除寬度和高度屬性——這將使版面配置具備回應式。設定為 false 時則相反。讀寫 boolean。

**傳回：**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

設定為 true 時，從 SVG 容器中排除寬度和高度屬性——這將使版面配置具備回應式。設定為 false 時則相反。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

取得或設定指示文字是否在不使用連字的情況下渲染的值。設定為 true 時，渲染輸出中會停用連字。預設此屬性為 false。

--------------------

> ```
> 範例：
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


**傳回：**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

取得或設定指示文字是否在不使用連字的情況下渲染的值。設定為 true 時，渲染輸出中會停用連字。預設此屬性為 false。

--------------------

> ```
> 範例：
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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> 範例：
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


**傳回：**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> 範例：
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
public abstract IInkOptions getInkOptions()
```

提供控制匯出文件中 Ink 物件外觀的選項。唯讀 [IInkOptions](../../com.aspose.slides/iinkoptions)

**傳回：**
[IInkOptions](../../com.aspose.slides/iinkoptions)