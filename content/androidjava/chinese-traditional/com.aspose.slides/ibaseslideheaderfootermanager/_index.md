---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides for Android 的 Java API 參考
description: 代表管理器，負責處理所有投影片類型的頁腳、日期時間及頁碼佔位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/ibaseslideheaderfootermanager/
---
**全部已實作的介面:**  
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

代表管理器，負責處理所有投影片類型的頁腳、日期時間、頁碼佔位符的行為。

## 方法

| 方法 | 描述 |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | 取得指示是否存在頁腳佔位符的值。 |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | 取得指示是否存在頁碼佔位符的值。 |
| [isDateTimeVisible()](#isDateTimeVisible--) | 取得指示是否存在日期時間佔位符的值。 |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | 變更投影片頁腳佔位符的可見性。 |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | 變更投影片頁碼佔位符的可見性。 |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | 變更投影片日期時間佔位符的可見性。 |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | 設定投影片頁腳佔位符的文字。 |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | 設定投影片日期時間佔位符的文字。 |

### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

取得指示是否存在頁腳佔位符的值。讀取布林值。

**回傳值:**
boolean

### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

取得指示是否存在頁碼佔位符的值。讀取布林值。

**回傳值:**
boolean

### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

取得指示是否存在日期時間佔位符的值。讀取布林值。

**回傳值:**
boolean

### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

變更投影片頁腳佔位符的可見性。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁腳佔位符可見，否則 - 隱藏它。 |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

變更投影片頁碼佔位符的可見性。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁碼佔位符可見，否則 - 隱藏它。 |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

變更投影片日期時間佔位符的可見性。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期時間佔位符可見，否則 - 隱藏它。 |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

設定投影片頁腳佔位符的文字。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

設定投影片日期時間佔位符的文字。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |