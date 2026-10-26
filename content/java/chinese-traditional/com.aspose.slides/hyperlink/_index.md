---
title: Hyperlink
second_title: Aspose.Slides for Java API 參考
description: 表示 Hyperlink。
type: docs
url: /zh-hant/com.aspose.slides/hyperlink/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有實作的介面：**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

表示 Hyperlink。

## 建構子

| 建構子 | 說明 |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | 建立 Hyperlink 的實例。 |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | 建立指向特定投影片的 Hyperlink 實例。 |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | 使用另一個 Hyperlink 作為來源，覆寫次要屬性，建立 Hyperlink 實例。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | 傳回特殊「do nothing」Hyperlink。 |
| [getMedia()](#getMedia--) | 傳回特殊「play mediafile」Hyperlink。 |
| [getNextSlide()](#getNextSlide--) | 傳回指向下一張投影片的 Hyperlink。 |
| [getPreviousSlide()](#getPreviousSlide--) | 傳回指向前一張投影片的 Hyperlink。 |
| [getFirstSlide()](#getFirstSlide--) | 傳回指向簡報第一張投影片的 Hyperlink。 |
| [getLastSlide()](#getLastSlide--) | 傳回指向簡報最後一張投影片的 Hyperlink。 |
| [getLastVievedSlide()](#getLastVievedSlide--) | 傳回指向最後檢視的投影片的 Hyperlink。 |
| [getEndShow()](#getEndShow--) | 傳回結束簡報的 Hyperlink。 |
| [getActionType()](#getActionType--) | 傳回 Hyperlink 動作的類型。 |
| [getExternalUrl()](#getExternalUrl--) | 指定外部 URL。 |
| [getTargetSlide()](#getTargetSlide--) | 如果 Hyperlink 目標為特定投影片，傳回該投影片。 |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 表示設定於此區段的 Hyperlink，且不考慮區段實際內容。 |
| [getTargetFrame()](#getTargetFrame--) | 傳回父 HTML frameset 中針對父 Hyperlink 目標的框架（若存在）。 |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 傳回父 HTML frameset 中針對父 Hyperlink 目標的框架（若存在）。 |
| [getTooltip()](#getTooltip--) | 傳回可能在使用者介面上顯示、與父 Hyperlink 相關的字串。 |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 傳回可能在使用者介面上顯示、與父 Hyperlink 相關的字串。 |
| [getHistory()](#getHistory--) | 決定在呼叫時是否將父 Hyperlink 的目標加入已檢視 Hyperlink 列表。 |
| [setHistory(boolean value)](#setHistory-boolean-) | 決定在呼叫時是否將父 Hyperlink 的目標加入已檢視 Hyperlink 列表。 |
| [getHighlightClick()](#getHighlightClick--) | 決定在點擊時是否突顯 Hyperlink。 |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | 決定在點擊時是否突顯 Hyperlink。 |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | 決定在點擊 Hyperlink 時是否停止聲音。 |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | 決定在點擊 Hyperlink 時是否停止聲音。 |
| [getSound()](#getSound--) | 表示 Hyperlink 正在播放的聲音。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 表示 Hyperlink 正在播放的聲音。 |
| [getColorSource()](#getColorSource--) | 表示 Hyperlink 顏色的來源——樣式或區段格式。 |
| [setColorSource(int value)](#setColorSource-int-) | 表示 Hyperlink 顏色的來源——樣式或區段格式。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷兩個 Hyperlink 實例是否相等。 |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 判斷兩個 Hyperlink 實例是否相等。 |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 測試兩個 Hyperlink 是否相等。 |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 測試兩個 Hyperlink 是否不相等。 |
| [hashCode()](#hashCode--) | 作為特定型別的雜湊函式，適用於雜湊演算法及如雜湊表之資料結構。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

建立 Hyperlink 的實例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL。 |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

建立指向特定投影片的 Hyperlink 實例。注意：建立的 Hyperlink 必須指派給同一簡報中的物件，否則連結將儲存為 NoAction。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 目標投影片。 |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

使用另一個 Hyperlink 作為來源，覆寫次要屬性，建立 Hyperlink 實例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | 來源 Hyperlink |
| targetFrame | java.lang.String | 目標框架 |
| tooltip | java.lang.String | 工具提示文字 |
| history | boolean | 決定在呼叫時是否將父 Hyperlink 的目標加入已檢視 Hyperlink 列表。 |
| stopSoundsOnClick | boolean | 決定在點擊 Hyperlink 時是否停止聲音。 |
| highlightClick | boolean | 決定在點擊時是否突顯 Hyperlink。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回值：**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

傳回特殊「do nothing」Hyperlink。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**傳回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

傳回特殊「play mediafile」Hyperlink。用於 AudioFrame 與 VideoFrame。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**傳回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

傳回指向下一張投影片的 Hyperlink。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**傳回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

傳回指向前一張投影片的 Hyperlink。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**傳回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

傳回指向簡報第一張投影片的 Hyperlink。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**傳回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

傳回指向簡報最後一張投影片的 Hyperlink。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**傳回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

傳回指向最後檢視的投影片的 Hyperlink。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**傳回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

傳回結束簡報的 Hyperlink。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**傳回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

傳回 Hyperlink 動作的類型。唯讀 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)。

**傳回值：**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

指定外部 URL。唯讀 String。

**傳回值：**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

如果 Hyperlink 目標為特定投影片，傳回該投影片。唯讀 [ISlide](../../com.aspose.slides/islide)。

**傳回值：**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

表示設定於此區段的 Hyperlink，且不考慮區段實際內容。

--------------------

PowerPoint 針對連結及其在區段中的文字有特別的行為。它允許以有效的 URL 形式建立超連結文字，與實際連結地址不同。此情況下，在編輯視窗中檢視連結時，文字會被更改以符合區段文字。此屬性表示超連結的原始值。

**傳回值：**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

傳回父 HTML frameset 中針對父 Hyperlink 目標的框架（若存在）。可讀寫 String。

**傳回值：**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

傳回父 HTML frameset 中針對父 Hyperlink 目標的框架（若存在）。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

傳回可能在使用者介面上顯示、與父 Hyperlink 相關的字串。可讀寫 String。

**傳回值：**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

傳回可能在使用者介面上顯示、與父 Hyperlink 相關的字串。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

決定在呼叫時是否將父 Hyperlink 的目標加入已檢視 Hyperlink 列表。可讀寫 boolean。

**傳回值：**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

決定在呼叫時是否將父 Hyperlink 的目標加入已檢視 Hyperlink 列表。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

決定在點擊時是否突顯 Hyperlink。可讀寫 boolean。

**傳回值：**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

決定在點擊時是否突顯 Hyperlink。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

決定在點擊 Hyperlink 時是否停止聲音。可讀寫 boolean。

**傳回值：**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

決定在點擊 Hyperlink 時是否停止聲音。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

表示 Hyperlink 正在播放的聲音。可讀寫 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Get the first shape hyperlink
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extract the hyperlink sound in byte array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回值：**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

表示 Hyperlink 正在播放的聲音。可讀寫 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 取得第一個形狀的超連結
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // 以位元組陣列提取超連結的聲音
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

表示 Hyperlink 顏色的來源——樣式或區段格式。可讀寫 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**傳回值：**
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

表示 Hyperlink 顏色的來源——樣式或區段格式。可讀寫 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷兩個 Hyperlink 實例是否相等。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要與目前 Hyperlink 比較的 Hyperlink。 |

**傳回值：**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

判斷兩個 Hyperlink 實例是否相等。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 要與目前 Hyperlink 比較的 Hyperlink。 |

**傳回值：**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

測試兩個 Hyperlink 是否相等。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第一個要測試的 Hyperlink。 |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第二個要測試的 Hyperlink。 |

**傳回值：**
boolean - **true** if hyperlinks are equal.

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

測試兩個 Hyperlink 是否不相等。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第一個要測試的 Hyperlink。 |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第二個要測試的 Hyperlink。 |

**傳回值：**
boolean - **false** if hyperlinks are equal.

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定型別的雜湊函式，適用於雜湊演算法及如雜湊表之資料結構。

**傳回值：**
int - URL 的雜湊碼。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回值：**
com.aspose.slides.IDOMObject