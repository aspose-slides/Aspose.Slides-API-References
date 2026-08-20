---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Java API 參考文件
description: 代表管理器，負責管理母版備註投影片的頁腳、日期時間、頁碼佔位符以及所有子佔位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/masternotesslideheaderfootermanager/
---
**繼承：**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**所有已實作介面：**
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

代表管理器，負責管理母版備註投影片的頁腳、日期時間、頁碼佔位符以及所有子佔位符的行為。子佔位符表示這些佔位符位於依賴的備註投影片中。依賴的備註投影片使用且依賴於母版備註投影片。
## 方法

| 方法 | 說明 |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | 變更母版備註投影片的標題佔位符以及所有子標題佔位符的可見性。 |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | 設定文字到母版備註投影片的標題佔位符以及所有子標題佔位符。 |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 變更母版投影片的頁腳佔位符以及所有子頁腳佔位符的可見性。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 變更母版投影片的頁碼佔位符以及所有子頁碼佔位符的可見性。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 變更母版投影片的日期時間佔位符以及所有子日期時間佔位符的可見性。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 設定文字到母版投影片的頁腳佔位符以及所有子頁腳佔位符。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 設定文字到母版投影片的日期時間佔位符以及所有子日期時間佔位符。 |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

變更母版備註投影片的標題佔位符以及所有子標題佔位符的可見性。子佔位符表示這些佔位符位於依賴的備註投影片中。依賴的備註投影片使用且依賴於母版備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使標題佔位符可見，否則隱藏它們。 |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

設定文字到母版備註投影片的標題佔位符以及所有子標題佔位符。子佔位符表示這些佔位符位於依賴的備註投影片中。依賴的備註投影片使用且依賴於母版備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

變更母版投影片的頁腳佔位符以及所有子頁腳佔位符的可見性。子佔位符表示這些佔位符位於依賴的備註投影片中。依賴的備註投影片使用且依賴於母版備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁腳佔位符可見，否則隱藏它們。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

變更母版投影片的頁碼佔位符以及所有子頁碼佔位符的可見性。子佔位符表示這些佔位符位於依賴的備註投影片中。依賴的備註投影片使用且依賴於母版備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁碼佔位符可見，否則隱藏它們。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

變更母版投影片的日期時間佔位符以及所有子日期時間佔位符的可見性。子佔位符表示這些佔位符位於依賴的備註投影片中。依賴的備註投影片使用且依賴於母版備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期時間佔位符可見，否則隱藏它們。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

設定文字到母版投影片的頁腳佔位符以及所有子頁腳佔位符。子佔位符表示這些佔位符位於依賴的備註投影片中。依賴的備註投影片使用且依賴於母版備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

設定文字到母版投影片的日期時間佔位符以及所有子日期時間佔位符。子佔位符表示這些佔位符位於依賴的備註投影片中。依賴的備註投影片使用且依賴於母版備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |