---
title: Hyperlink
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一個超連結。
type: docs
url: /zh-hant/com.aspose.slides/hyperlink/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

代表一個超連結。
## 建構式

| 建構式 | 描述 |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | 建立一個超連結的實例。 |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | 建立一個指向特定投影片的超連結實例。 |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | 使用另一個超連結作為來源，覆寫次要屬性，建立超連結實例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | 傳回一個特殊的「不執行」超連結。 |
| [getMedia()](#getMedia--) | 傳回一個特殊的「播放媒體檔案」超連結。 |
| [getNextSlide()](#getNextSlide--) | 傳回指向下一張投影片的超連結。 |
| [getPreviousSlide()](#getPreviousSlide--) | 傳回指向上一張投影片的超連結。 |
| [getFirstSlide()](#getFirstSlide--) | 傳回指向簡報第一張投影片的超連結。 |
| [getLastSlide()](#getLastSlide--) | 傳回指向簡報最後一張投影片的超連結。 |
| [getLastVievedSlide()](#getLastVievedSlide--) | 傳回指向最近檢視過的投影片的超連結。 |
| [getEndShow()](#getEndShow--) | 傳回結束簡報的超連結。 |
| [getActionType()](#getActionType--) | 傳回超連結動作的類型。 |
| [getExternalUrl()](#getExternalUrl--) | 指定外部 URL。 |
| [getTargetSlide()](#getTargetSlide--) | 如果超連結指向特定投影片，則傳回該投影片。 |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 代表即使與該部分的實際內容無關也會為此部分設定的超連結。 |
| [getTargetFrame()](#getTargetFrame--) | 在存在時，傳回父超連結目標所在的父 HTML 框架集中的框架。 |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 在存在時，傳回父超連結目標所在的父 HTML 框架集中的框架。 |
| [getTooltip()](#getTooltip--) | 傳回可能在使用者介面中顯示，與父超連結相關聯的字串。 |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 傳回可能在使用者介面中顯示，與父超連結相關聯的字串。 |
| [getHistory()](#getHistory--) | 判斷在呼叫時，是否將父超連結的目標加入已檢視超連結清單。 |
| [setHistory(boolean value)](#setHistory-boolean-) | 判斷在呼叫時，是否將父超連結的目標加入已檢視超連結清單。 |
| [getHighlightClick()](#getHighlightClick--) | 判斷點擊時是否應突出顯示該超連結。 |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | 判斷點擊時是否應突出顯示該超連結。 |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | 判斷點擊超連結時是否應停止聲音。 |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | 判斷點擊超連結時是否應停止聲音。 |
| [getSound()](#getSound--) | 代表超連結的播放聲音。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 代表超連結的播放聲音。 |
| [getColorSource()](#getColorSource--) | 代表超連結顏色的來源——樣式或部分格式。 |
| [setColorSource(int value)](#setColorSource-int-) | 代表超連結顏色的來源——樣式或部分格式。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷兩個 Hyperlink 實例是否相等。 |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 判斷兩個 Hyperlink 實例是否相等。 |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 測試兩個超連結是否相等。 |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 測試兩個超連結是否不相等。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式，可用於雜湊演算法和像雜湊表之類的資料結構。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

建立一個超連結的實例。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| url | java.lang.String | 超連結 URL。 |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

建立一個指向特定投影片的超連結實例。註：建立的超連結應指派給同一簡報中的某個物件，否則連結將儲存為 NoAction。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 目標投影片。 |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

使用另一個超連結作為來源，覆寫次要屬性，建立超連結實例。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | 來源超連結 |
| targetFrame | java.lang.String | 目標框架 |
| tooltip | java.lang.String | 提示文字 |
| history | boolean | 判斷在呼叫時，是否將父超連結的目標加入已檢視超連結清單。 |
| stopSoundsOnClick | boolean | 判斷點擊超連結時是否應停止聲音。 |
| highlightClick | boolean | 判斷點擊時是否應突出顯示該超連結。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**回傳:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

傳回一個特殊的「不執行」超連結。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**回傳:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

傳回一個特殊的「播放媒體檔案」超連結。用於 AudioFrame 和 VideoFrame。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**回傳:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

傳回指向下一張投影片的超連結。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**回傳:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

傳回指向上一張投影片的超連結。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**回傳:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

傳回指向簡報第一張投影片的超連結。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**回傳:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

傳回指向簡報最後一張投影片的超連結。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**回傳:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

傳回指向最近檢視過的投影片的超連結。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**回傳:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

傳回結束簡報的超連結。唯讀 [Hyperlink](../../com.aspose.slides/hyperlink)。

**回傳:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

傳回超連結動作的類型。唯讀 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)。

**回傳:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

指定外部 URL。唯讀 String。

**回傳:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

如果超連結指向特定投影片，則傳回該投影片。唯讀 [ISlide](../../com.aspose.slides/islide)。

**回傳:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

代表即使與該部分的實際內容無關也會為此部分設定的超連結。

--------------------

PowerPoint 對於投影片中部分的連結及其相應文字有特別的行為。它允許以有效的 URL 形式為超連結建立文字，該文字可能與實際連結地址不同。此情況下，當您在編輯視窗中查看連結時，會被更改為符合文字部分。此屬性代表超連結的原始值。

**回傳:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

在存在時，傳回父超連結目標所在的父 HTML 框架集中的框架。讀寫 String。

**回傳:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

在存在時，傳回父超連結目標所在的父 HTML 框架集中的框架。讀寫 String。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

傳回可能在使用者介面中顯示，與父超連結相關聯的字串。讀寫 String。

**回傳:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

傳回可能在使用者介面中顯示，與父超連結相關聯的字串。讀寫 String。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

判斷在呼叫時，是否將父超連結的目標加入已檢視超連結清單。讀寫 boolean。

**回傳:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

判斷在呼叫時，是否將父超連結的目標加入已檢視超連結清單。讀寫 boolean。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

判斷點擊時是否應突出顯示該超連結。讀寫 boolean。

**回傳:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

判斷點擊時是否應突出顯示該超連結。讀寫 boolean。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

判斷點擊超連結時是否應停止聲音。讀寫 boolean。

**回傳:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

判斷點擊超連結時是否應停止聲音。讀寫 boolean。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

代表超連結的播放聲音。讀寫 [IAudio](../../com.aspose.slides/iaudio)。

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
>          // 以位元組陣列提取超連結音效
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**回傳:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

代表超連結的播放聲音。讀寫 [IAudio](../../com.aspose.slides/iaudio)。

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
>          // 以位元組陣列提取超連結音訊
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

代表超連結顏色的來源——樣式或部分格式。讀寫 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**回傳:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

代表超連結顏色的來源——樣式或部分格式。讀寫 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷兩個 Hyperlink 實例是否相等。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 與目前 Hyperlink 比較的 Hyperlink。 |

**回傳:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

判斷兩個 Hyperlink 實例是否相等。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 與目前 Hyperlink 比較的 Hyperlink。 |

**回傳:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

測試兩個超連結是否相等。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第一個要測試的超連結。 |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第二個要測試的超連結。 |

**回傳:**
boolean - **true** if hyperlinks are equal.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

測試兩個超連結是否不相等。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第一個要測試的超連結。 |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第二個要測試的超連結。 |

**回傳:**
boolean - **false** if hyperlinks are equal.
### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式，可用於雜湊演算法和像雜湊表之類的資料結構。

**回傳:**
int - Hash code for an URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**回傳:**
com.aspose.slides.IDOMObject