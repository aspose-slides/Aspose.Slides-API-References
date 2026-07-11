---
title: Html5Options
second_title: Aspose.Slides for Java API 參考
description: 代表 HTML5 匯出選項。
type: docs
url: /zh-hant/com.aspose.slides/html5options/
---
**繼承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有已實作的介面:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

代表 HTML5 匯出選項。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [Html5Options()](#Html5Options--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | Returns or sets transitions animation option. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | Returns or sets transitions animation option. |
| [getAnimateShapes()](#getAnimateShapes--) | Returns or sets shapes animation option. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | Returns or sets shapes animation option. |
| [getEmbedImages()](#getEmbedImages--) | Returns or sets images embedding option. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | Returns or sets images embedding option. |
| [getOutputPath()](#getOutputPath--) | Determines where external resources should be stored. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | Determines where external resources should be stored. |
| [getPicturesCompression()](#getPicturesCompression--) | Represents the pictures compression level |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Represents the pictures compression level |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Gets or sets a value indicating whether text is rendered without using ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Gets or sets a value indicating whether text is rendered without using ligatures. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```


Default constructor.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```

取得或設定過渡動畫選項。讀寫布林值。

--------------------

> ```
> 範例：
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```

取得或設定過渡動畫選項。讀寫布林值。

--------------------

> ```
> 範例：
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```

取得或設定形狀動畫選項。讀寫布林值。

--------------------

> ```
> 範例：
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```

取得或設定形狀動畫選項。讀寫布林值。

--------------------

> ```
> 範例：
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```

取得或設定圖像嵌入選項。讀寫布林值。

--------------------

> ```
> 範例：
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```


Returns or sets images embedding option. Read/write boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```

決定外部資源應儲存的位置。讀寫字串。

--------------------

> ```
> 範例：
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```

決定外部資源應儲存的位置。讀寫字串。

--------------------

> ```
> 範例：
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

代表圖片壓縮等級

**返回值:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

代表圖片壓縮等級

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```
Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // 停用文字渲染中的連字
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // 停用文字渲染中的連字
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

取得或設定在匯出簡報時投影片於頁面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> 範例：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)


取得或設定在匯出簡報時投影片在頁面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |