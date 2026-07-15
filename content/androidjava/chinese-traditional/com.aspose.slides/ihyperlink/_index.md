---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: 表示超連結。
type: docs
url: /zh-hant/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

表示超連結。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getActionType()](#getActionType--) | 返回 HyperLinkEx 的動作類型。 |
| [getExternalUrl()](#getExternalUrl--) | 指定外部 URL。如果此屬性變為非 null，則屬性 TargetSlide 變為 null。 |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 表示為此段落設定的超連結，且不考慮段落的實際內容。 |
| [getTargetSlide()](#getTargetSlide--) | 如果 HyperlinkEx 目標為特定投影片，則返回該投影片。 |
| [getTargetFrame()](#getTargetFrame--) | 返回父 HTML 框架集中父超連結目標的框架（若存在）。 |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 返回父 HTML 框架集中父超連結目標的框架（若存在）。 |
| [getTooltip()](#getTooltip--) | 返回可能在使用者介面中顯示、與父超連結相關聯的字串。 |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 返回可能在使用者介面中顯示、與父超連結相關聯的字串。 |
| [getHistory()](#getHistory--) | 判斷在呼叫父超連結時，其目標是否應加入已檢視超連結清單。 |
| [setHistory(boolean value)](#setHistory-boolean-) | 判斷在呼叫父超連結時，其目標是否應加入已檢視超連結清單。 |
| [getHighlightClick()](#getHighlightClick--) | 判斷點擊時是否應將超連結突顯。 |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | 判斷點擊時是否應將超連結突顯。 |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | 判斷在點擊超連結時是否應停止聲音。 |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | 判斷在點擊超連結時是否應停止聲音。 |
| [getSound()](#getSound--) | 表示超連結的播放聲音。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 表示超連結的播放聲音。 |
| [getColorSource()](#getColorSource--) | 表示超連結顏色的來源─樣式或段落格式。 |
| [setColorSource(int value)](#setColorSource-int-) | 表示超連結顏色的來源─樣式或段落格式。 |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 判斷兩個 Hyperlink 實例是否相等。 |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

返回 HyperLinkEx 的動作類型。唯讀 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)。

**返回:**  
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

指定外部 URL。如果此屬性變為非 null，則屬性 TargetSlide 變為 null。唯讀 String。

**返回:**  
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

表示為此段落設定的超連結，且不考慮段落的實際內容。

---

PowerPoint 針對段落中的連結及其相應文字有特定行為。它允許以有效的 URL 形式為超連結建立文字，而此 URL 可能與連結的實際位址不同。在此情況下，當您在編輯視窗中檢視連結時，會被更改為符合文字段落。此屬性表示超連結的原始值。

**返回:**  
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

如果 HyperlinkEx 目標為特定投影片，則返回該投影片。如果此屬性變為非 null，則屬性 ExternalUrl 變為 null。唯讀 [ISlide](../../com.aspose.slides/islide)。

**返回:**  
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

返回父 HTML 框架集中父超連結目標的框架（若存在）。讀寫 String。

**返回:**  
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

返回父 HTML 框架集中父超連結目標的框架（若存在）。讀寫 String。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

返回可能在使用者介面中顯示、與父超連結相關聯的字串。讀寫 String。

**返回:**  
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

返回可能在使用者介面中顯示、與父超連結相關聯的字串。讀寫 String。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

判斷在呼叫父超連結時，其目標是否應加入已檢視超連結清單。讀寫 boolean。

**返回:**  
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

判斷在呼叫父超連結時，其目標是否應加入已檢視超連結清單。讀寫 boolean。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

判斷點擊時是否應將超連結突顯。讀寫 boolean。

**返回:**  
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

判斷點擊時是否應將超連結突顯。讀寫 boolean。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

判斷在點擊超連結時是否應停止聲音。讀寫 boolean。

**返回:**  
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

判斷在點擊超連結時是否應停止聲音。讀寫 boolean。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

表示超連結的播放聲音。讀寫 [IAudio](../../com.aspose.slides/iaudio)。

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 獲取第一個形狀的超連結
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


**返回:**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

表示超連結的播放聲音。讀寫 [IAudio](../../com.aspose.slides/iaudio)。

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 獲取第一個形狀的超連結
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

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

表示超連結顏色的來源─樣式或段落格式。讀寫 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**返回:**  
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

表示超連結顏色的來源─樣式或段落格式。讀寫 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

判斷兩個 Hyperlink 實例是否相等。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 要與目前的 Hyperlink 比較的 Hyperlink。 |

**返回:**  
boolean – **true** 若指定的 Hyperlink 與目前的 Hyperlink 相等；否則 **false**。