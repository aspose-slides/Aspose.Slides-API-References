---
title: BaseSlideHeaderFooterManager
second_title: Aspose.Slides for Android 的 Java API 參考
description: 代表管理器，保存所有投影片類型的頁腳、日期時間、頁碼佔位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/baseslideheaderfootermanager/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)  
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

代表管理器，保存所有投影片類型的頁腳、日期時間、頁碼佔位符的行為。

## 方法

| 方法 | 說明 |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | 取得指示頁腳佔位符是否存在的值。 |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | 取得指示頁碼佔位符是否存在的值。 |
| [isDateTimeVisible()](#isDateTimeVisible--) | 取得指示日期時間佔位符是否存在的值。 |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | 變更投影片頁腳佔位符的可見性。 |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | 變更投影片頁碼佔位符的可見性。 |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | 變更投影片日期時間佔位符的可見性。 |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | 設定投影片頁腳佔位符的文字。 |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | 設定投影片日期時間佔位符的文字。 |

### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

取得指示頁腳佔位符是否存在的值。讀取 boolean。

**回傳值:**  
boolean

### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

取得指示頁碼佔位符是否存在的值。讀取 boolean。

**回傳值:**  
boolean

### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

取得指示日期時間佔位符是否存在的值。讀取 boolean。

**回傳值:**  
boolean

### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

變更投影片頁腳佔位符的可見性。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁腳佔位符可見，否則隱藏它。 |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

變更投影片頁碼佔位符的可見性。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁碼佔位符可見，否則隱藏它。 |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

變更投影片日期時間佔位符的可見性。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期時間佔位符可見，否則隱藏它。 |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

設定投影片頁腳佔位符的文字。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 設定的文字。 |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

設定投影片日期時間佔位符的文字。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 設定的文字。 |