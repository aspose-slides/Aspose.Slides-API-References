---
title: ISwfOptions
second_title: Aspose.Slides for Android via Java API 參考
description: 提供控制簡報以 SWF 格式儲存方式的選項。
type: docs
url: /zh-hant/com.aspose.slides/iswfoptions/
---
**所有已實作的介面：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

提供控制演示文稿以 SWF 格式儲存方式的選項。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 指定生成的 SWF 文檔是否應被壓縮。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 指定生成的 SWF 文檔是否應被壓縮。 |
| [getViewerIncluded()](#getViewerIncluded--) | 指定生成的 SWF 文檔是否應包含內建的文件檢視器。 |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | 指定生成的 SWF 文檔是否應包含內建的文件檢視器。 |
| [getShowPageBorder()](#getShowPageBorder--) | 指定是否顯示頁面周圍的邊框。 |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | 指定是否顯示頁面周圍的邊框。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文件是否應包含隱藏投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文件是否應包含隱藏投影片。 |
| [getShowFullScreen()](#getShowFullScreen--) | 顯示/隱藏全螢幕按鈕。 |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | 顯示/隱藏全螢幕按鈕。 |
| [getShowPageStepper()](#getShowPageStepper--) | 顯示/隱藏頁面步進器。 |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | 顯示/隱藏頁面步進器。 |
| [getShowSearch()](#getShowSearch--) | 顯示/隱藏搜尋區段。 |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | 顯示/隱藏搜尋區段。 |
| [getShowTopPane()](#getShowTopPane--) | 顯示/隱藏整個頂部面板。 |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | 顯示/隱藏整個頂部面板。 |
| [getShowBottomPane()](#getShowBottomPane--) | 顯示/隱藏底部面板。 |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | 顯示/隱藏底部面板。 |
| [getShowLeftPane()](#getShowLeftPane--) | 顯示/隱藏左側面板。 |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | 顯示/隱藏左側面板。 |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | 以開啟的左側面板開始。 |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | 以開啟的左側面板開始。 |
| [getEnableContextMenu()](#getEnableContextMenu--) | 啟用/停用快顯功能表。 |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | 啟用/停用快顯功能表。 |
| [getLogoImageBytes()](#getLogoImageBytes--) | 在檢視器右上角顯示為標誌的圖像。 |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | 在檢視器右上角顯示為標誌的圖像。 |
| [getLogoLink()](#getLogoLink--) | 取得或設定標誌的完整超連結位址。 |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | 取得或設定標誌的完整超連結位址。 |
| [getJpegQuality()](#getJpegQuality--) | 指定 JPEG 圖像的品質。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 指定 JPEG 圖像的品質。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

指定生成的 SWF 文檔是否應被壓縮。預設為 true。

**返回值：**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

指定生成的 SWF 文檔是否應被壓縮。預設為 true。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

指定生成的 SWF 文檔是否應包含內建的文件檢視器。預設為 true。

**返回值：**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

指定生成的 SWF 文檔是否應包含內建的文件檢視器。預設為 true。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

指定是否顯示頁面周圍的邊框。預設為 true。

**返回值：**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

指定是否顯示頁面周圍的邊框。預設為 true。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定生成的文件是否應包含隱藏投影片。預設為 false。

**返回值：**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定生成的文件是否應包含隱藏投影片。預設為 false。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

顯示/隱藏全螢幕按鈕。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

顯示/隱藏全螢幕按鈕。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

顯示/隱藏頁面步進器。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

顯示/隱藏頁面步進器。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

顯示/隱藏搜尋區段。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

顯示/隱藏搜尋區段。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

顯示/隱藏整個頂部面板。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

顯示/隱藏整個頂部面板。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

顯示/隱藏底部面板。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

顯示/隱藏底部面板。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

顯示/隱藏左側面板。可在 flashvars 中覆寫。預設為 true。

**返回值：**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

顯示/隱藏左側面板。可在 flashvars 中覆寫。預設為 true。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

以開啟的左側面板開始。可在 flashvars 中覆寫。預設為 false。

**返回值：**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

以開啟的左側面板開始。可在 flashvars 中覆寫。預設為 false。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

啟用/停用快顯功能表。預設為 true。

**返回值：**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

啟用/停用快顯功能表。預設為 true。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

將在檢視器右上角顯示為標誌的圖像。圖像應為 32x64 像素的 PNG 圖片，否則標誌可能無法正確顯示。

**返回值：**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

將在檢視器右上角顯示為標誌的圖像。圖像應為 32x64 像素的 PNG 圖片，否則標誌可能無法正確顯示。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

取得或設定標誌的完整超連結位址。僅在指定 (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) 時才會生效。

**返回值：**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

取得或設定標誌的完整超連結位址。僅在指定 (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) 時才會生效。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

指定 JPEG 圖像的品質。預設為 95。

**返回值：**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

指定 JPEG 圖像的品質。預設為 95。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。此屬性不支援指派類型為 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 的物件。

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。此屬性不支援指派類型為 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 的物件。

--------------------

> ```
> 範例：
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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |