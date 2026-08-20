---
title: XpsOptions
second_title: Aspose.Slides for Java API 參考
description: 提供控制簡報以 XPS 格式儲存的選項。
type: docs
url: /zh-hant/com.aspose.slides/xpsoptions/
---
**繼承關係：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**全部實作的介面：**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

提供控制簡報以 XPS 格式儲存的選項。

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // 實例化一個代表簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // 將簡報儲存為 XPS 文件
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // 實例化一個代表簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // 實例化 TiffOptions 類別
>      XpsOptions options = new XpsOptions();
>      // 將中繼檔案另存為 PNG
>      options.setSaveMetafilesAsPng(true);
>      // 將簡報儲存為 XPS 文件
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | 預設建構函式。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否應包含隱藏投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否應包含隱藏投影片。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 設為 true 以將簡報中使用的所有中繼檔案轉換為 PNG 圖片。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 設為 true 以將簡報中使用的所有中繼檔案轉換為 PNG 圖片。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 設為 true 以在每張投影片周圍繪製黑色框線。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 設為 true 以在每張投影片周圍繪製黑色框線。 |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

預設建構函式。

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**返回值:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

設為 true 以將簡報中使用的所有中繼檔案轉換為 PNG 圖片。可讀寫 boolean。

--------------------

預設為 **true**。

**返回值:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

設為 true 以將簡報中使用的所有中繼檔案轉換為 PNG 圖片。可讀寫 boolean。

--------------------

預設為 **true**。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

設為 true 以在每張投影片周圍繪製黑色框線。可讀寫 boolean。

--------------------

預設為 **false**。

**返回值:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

設為 true 以在每張投影片周圍繪製黑色框線。可讀寫 boolean。

--------------------

預設為 **false**。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |