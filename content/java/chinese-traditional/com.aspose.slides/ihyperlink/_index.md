---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Represents a hyperlink.
type: docs
url: /zh-hant/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

表示超連結。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getActionType()](#getActionType--) | 傳回 HyperLinkEx 的動作類型。 |
| [getExternalUrl()](#getExternalUrl--) | 指定外部 URL；如果此屬性不為 null，則屬性 TargetSlide 會變為 null。 |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 表示設定於此部分的超連結，與該部分的實際內容無關。 |
| [getTargetSlide()](#getTargetSlide--) | 如果 HyperlinkEx 目標為特定投影片，則傳回該投影片。 |
| [getTargetFrame()](#getTargetFrame--) | 傳回父 HTML 框架集中父超連結目標的框架（若存在）。 |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 傳回父 HTML 框架集中父超連結目標的框架（若存在）。 |
| [getTooltip()](#getTooltip--) | 傳回可能在使用者介面中顯示的字串，與父超連結相關聯。 |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 傳回可能在使用者介面中顯示的字串，與父超連結相關聯。 |
| [getHistory()](#getHistory--) | 決定當呼叫時，是否將父超連結的目標加入已檢視超連結的清單。 |
| [setHistory(boolean value)](#setHistory-boolean-) | 決定當呼叫時，是否將父超連結的目標加入已檢視超連結的清單。 |
| [getHighlightClick()](#getHighlightClick--) | 決定點選時是否應突出顯示超連結。 |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | 決定點選時是否應突出顯示超連結。 |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | 決定在點擊超連結時是否應停止聲音。 |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | 決定在點擊超連結時是否應停止聲音。 |
| [getSound()](#getSound--) | 表示超連結的播放聲音。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 表示超連結的播放聲音。 |
| [getColorSource()](#getColorSource--) | 表示超連結顏色的來源—樣式或部分格式。 |
| [setColorSource(int value)](#setColorSource-int-) | 表示超連結顏色的來源—樣式或部分格式。 |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 決定兩個 Hyperlink 實例是否相等。 |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

傳回 HyperLinkEx 的動作類型。唯讀 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)。

**傳回:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

指定外部 URL；如果此屬性不為 null，則屬性 TargetSlide 會變為 null。唯讀 String。

**傳回:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

表示設定於此部分的超連結，與該部分的實際內容無關。

--------------------

PowerPoint 對於投影片中連結及其對應的文字有特定的行為。它允許以有效的 URL 形式為超連結建立文字，該文字可能與連結的實際位址不同。在此情況下，當您在編輯視窗中檢視連結時，它會被變更為符合文字部分。此屬性表示超連結的原始值。

**傳回:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

如果 HyperlinkEx 目標為特定投影片，則傳回該投影片。如果此屬性變為不為 null，則屬性 ExternalUrl 會變為 null。唯讀 [ISlide](../../com.aspose.slides/islide)。

**傳回:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

傳回父 HTML 框架集中父超連結目標的框架（若存在）。可讀寫 String。

**傳回:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

傳回父 HTML 框架集中父超連結目標的框架（若存在）。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

傳回可能在使用者介面中顯示的字串，與父超連結相關聯。可讀寫 String。

**傳回:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

傳回可能在使用者介面中顯示的字串，與父超連結相關聯。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

決定當呼叫時，是否將父超連結的目標加入已檢視超連結的清單。可讀寫 boolean。

**傳回:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

決定當呼叫時，是否將父超連結的目標加入已檢視超連結的清單。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

決定點選時是否應突出顯示超連結。可讀寫 boolean。

**傳回:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

決定點選時是否應突出顯示超連結。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

決定在點擊超連結時是否應停止聲音。可讀寫 boolean。

**傳回:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

決定在點擊超連結時是否應停止聲音。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

表示超連結的播放聲音。可讀寫 [IAudio](../../com.aspose.slides/iaudio)。

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
>          // 以位元組陣列提取超連結聲音
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**傳回:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

表示超連結的播放聲音。可讀寫 [IAudio](../../com.aspose.slides/iaudio)。
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
>          // 以位元組陣列提取超連結聲音
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

表示超連結顏色的來源—樣式或部分格式。可讀寫 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**傳回:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

表示超連結顏色的來源—樣式或部分格式。可讀寫 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

決定兩個 Hyperlink 實例是否相等。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 要與目前 Hyperlink 比較的 Hyperlink。 |

**傳回:**
boolean - **true** 若指定的 Hyperlink 與當前 Hyperlink 相等；否則 **false**.