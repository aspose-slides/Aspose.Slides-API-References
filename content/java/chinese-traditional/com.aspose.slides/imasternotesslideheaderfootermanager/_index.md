---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Java API 參考
description: 表示管理員，負責管理主備註投影片頁腳、日期時間、頁碼佔位符以及所有子佔位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**所有實作的介面：**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

表示管理員，負責管理主備註投影片頁腳、日期時間、頁碼佔位符以及所有子佔位符的行為。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。
## 方法

| 方法 | 說明 |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | 變更主備註投影片標題佔位符以及所有子標題佔位符的可見性。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。 |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | 設定文字至主備註投影片標題佔位符及所有子標題佔位符。 |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 變更主備註投影片頁腳佔位符以及所有子頁腳佔位符的可見性。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 變更主備註投影片頁碼佔位符以及所有子頁碼佔位符的可見性。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 變更主備註投影片日期時間佔位符以及所有子日期時間佔位符的可見性。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 設定文字至主備註投影片頁腳佔位符及所有子頁腳佔位符。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 設定文字至主備註投影片日期時間佔位符及所有子日期時間佔位符。 |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

變更主備註投影片標題佔位符以及所有子標題佔位符的可見性。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使標題佔位符可見，否則 - 隱藏它們。 |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

設定文字至主備註投影片標題佔位符及所有子標題佔位符。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

變更主備註投影片頁腳佔位符以及所有子頁腳佔位符的可見性。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁腳佔位符可見，否則 - 隱藏它們。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

變更主備註投影片頁碼佔位符以及所有子頁碼佔位符的可見性。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁碼佔位符可見，否則 - 隱藏它們。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

變更主備註投影片日期時間佔位符以及所有子日期時間佔位符的可見性。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期時間佔位符可見，否則 - 隱藏它們。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

設定文字至主備註投影片頁腳佔位符及所有子頁腳佔位符。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

設定文字至主備註投影片日期時間佔位符及所有子日期時間佔位符。子佔位符表示佔位符位於相依備註投影片上。相依備註投影片使用並依賴於主備註投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |