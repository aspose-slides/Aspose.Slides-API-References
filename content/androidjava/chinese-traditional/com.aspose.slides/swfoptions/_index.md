---
title: SwfOptions
second_title: Aspose.Slides 用於 Android 的 Java API 參考
description: 提供控制演示文稿以 Swf 格式儲存的選項。
type: docs
url: /zh-hant/com.aspose.slides/swfoptions/
---
**繼承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**已實作的介面：**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

提供控制演示文稿以 Swf 格式儲存的選項。

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // 實例化一個代表簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // 保存簡報和註解頁面
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 建構子

| 建構子 | 說明 |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | 預設建構子。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否應包含隱藏投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否應包含隱藏投影片。 |
| [getCompressed()](#getCompressed--) | 指定產生的 SWF 文件是否應壓縮。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 指定產生的 SWF 文件是否應壓縮。 |
| [getViewerIncluded()](#getViewerIncluded--) | 指定產生的 SWF 文件是否應包含整合的文件檢視器。 |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | 指定產生的 SWF 文件是否應包含整合的文件檢視器。 |
| [getShowPageBorder()](#getShowPageBorder--) | 指定是否應顯示頁面周圍的邊框。 |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | 指定是否應顯示頁面周圍的邊框。 |
| [getShowFullScreen()](#getShowFullScreen--) | 顯示/隱藏全螢幕按鈕。 |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | 顯示/隱藏全螢幕按鈕。 |
| [getShowPageStepper()](#getShowPageStepper--) | 顯示/隱藏頁面步進器。 |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | 顯示/隱藏頁面步進器。 |
| [getShowSearch()](#getShowSearch--) | 顯示/隱藏搜尋區段。 |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | 顯示/隱藏搜尋區段。 |
| [getShowTopPane()](#getShowTopPane--) | 顯示/隱藏整個上方面板。 |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | 顯示/隱藏整個上方面板。 |
| [getShowBottomPane()](#getShowBottomPane--) | 顯示/隱藏下方面板。 |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | 顯示/隱藏下方面板。 |
| [getShowLeftPane()](#getShowLeftPane--) | 顯示/隱藏左側面板。 |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | 顯示/隱藏左側面板。 |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | 以開啟的左側面板開始。 |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | 以開啟的左側面板開始。 |
| [getEnableContextMenu()](#getEnableContextMenu--) | 啟用/停用右鍵功能表。 |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | 啟用/停用右鍵功能表。 |
| [getLogoImageBytes()](#getLogoImageBytes--) | 將顯示於檢視器右上角的標誌圖像。 |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | 將顯示於檢視器右上角的標誌圖像。 |
| [getLogoLink()](#getLogoLink--) | 取得或設定標誌的完整超連結位址。 |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | 取得或設定標誌的完整超連結位址。 |
| [getJpegQuality()](#getJpegQuality--) | 指定 JPEG 影像的品質。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 指定 JPEG 影像的品質。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 取得或設定匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時投影片在頁面上的排列模式。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 取得或設定匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時投影片在頁面上的排列模式。 |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```


預設建構子。

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


指定產生的文件是否應包含隱藏投影片。預設為 false。

**返回值：**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


指定產生的文件是否應包含隱藏投影片。預設為 false。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


指定產生的 SWF 文件是否應壓縮。預設為 true。

**返回值：**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


指定產生的 SWF 文件是否應壓縮。預設為 true。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


指定產生的 SWF 文件是否應包含整合的文件檢視器。預設為 true。

**返回值：**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


指定產生的 SWF 文件是否應包含整合的文件檢視器。預設為 true。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


指定是否應顯示頁面周圍的邊框。預設為 true。

**返回值：**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


指定是否應顯示頁面周圍的邊框。預設為 true。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


顯示/隱藏全螢幕按鈕。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


顯示/隱藏全螢幕按鈕。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


顯示/隱藏頁面步進器。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


顯示/隱藏頁面步進器。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


顯示/隱藏搜尋區段。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


顯示/隱藏搜尋區段。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


顯示/隱藏整個上方面板。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


顯示/隱藏整個上方面板。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


顯示/隱藏下方面板。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


顯示/隱藏下方面板。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


顯示/隱藏左側面板。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


顯示/隱藏左側面板。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


以開啟的左側面板開始。可在 flashvars 中覆寫。預設為 false。

**返回值：**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


以開啟的左側面板開始。可在 flashvars 中覆寫。預設為 false。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


啟用/停用右鍵功能表。預設為 true。

**返回值：**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


啟用/停用右鍵功能表。預設為 true。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


將顯示於檢視器右上角的標誌圖像。圖像應為 32x64 像素的 PNG，否則可能顯示不正常。

**返回值：**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


將顯示於檢視器右上角的標誌圖像。圖像應為 32x64 像素的 PNG，否則可能顯示不正常。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


取得或設定標誌的完整超連結位址。僅在指定 (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) 時有效。

**返回值：**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


取得或設定標誌的完整超連結位址。僅在指定 (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) 時有效。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


指定 JPEG 影像的品質。預設為 95。

**返回值：**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


指定 JPEG 影像的品質。預設為 95。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


取得或設定匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時投影片在頁面上的排列模式。此屬性不支援指派類型為 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 的物件。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值：**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


取得或設定匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時投影片在頁面上的排列模式。此屬性不支援指派類型為 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 的物件。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |