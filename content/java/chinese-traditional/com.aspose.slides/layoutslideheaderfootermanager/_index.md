---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides for Java API 參考
description: 代表管理器，負責布局投影片的頁腳、日期時間、頁碼佔位符以及所有子佔位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/layoutslideheaderfootermanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

代表管理器，其負責布局投影片頁腳、日期時間、頁碼佔位符以及所有子佔位符的行為。子佔位符表示佔位符位於依賴投影片上。依賴投影片使用並依賴於布局投影片。
## 方法

| 方法 | 說明 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 變更布局投影片頁腳佔位符以及所有子頁腳佔位符的可見性。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 變更布局投影片頁碼佔位符以及所有子頁碼佔位符的可見性。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 變更布局投影片日期時間佔位符以及所有子日期時間佔位符的可見性。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 設定文字至布局投影片頁腳佔位符及所有子頁腳佔位符。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 設定文字至布局投影片日期時間佔位符及所有子日期時間佔位符。 |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

變更布局投影片頁腳佔位符以及所有子頁腳佔位符的可見性。子佔位符表示佔位符位於依賴投影片上。依賴投影片使用並依賴於母片。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁腳佔位符可見，否則隱藏。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

變更布局投影片頁碼佔位符以及所有子頁碼佔位符的可見性。子佔位符表示佔位符位於依賴投影片上。依賴投影片使用並依賴於布局投影片。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁號佔位符可見，否則隱藏。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

變更布局投影片日期時間佔位符以及所有子日期時間佔位符的可見性。子佔位符表示佔位符位於依賴投影片上。依賴投影片使用並依賴於布局投影片。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期時間佔位符可見，否則隱藏。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

設定文字至布局投影片頁腳佔位符及所有子頁腳佔位符。子佔位符表示佔位符位於依賴投影片上。依賴投影片使用並依賴於布局投影片。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

設定文字至布局投影片日期時間佔位符及所有子日期時間佔位符。子佔位符表示佔位符位於依賴投影片上。依賴投影片使用並依賴於布局投影片。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |