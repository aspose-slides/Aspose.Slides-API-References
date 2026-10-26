---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides for Android via Java API 參考
description: 表示管理員，負責控制簡報中所有頁腳、日期時間與頁碼佔位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/ipresentationheaderfootermanager/
---
**所有實作的介面:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

代表管理員，負責控制簡報中所有頁腳、日期時間與頁碼佔位符的行為。
## 方法

| 方法 | 說明 |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | 變更所有標頭佔位符的可見性，包括備註母片、備註投影片以及講義母片。 |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | 變更所有頁腳佔位符的可見性，包括母片投影片、版面配置投影片以及投影片本身。 |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | 變更所有頁碼佔位符的可見性，包括母片投影片、版面配置投影片以及投影片本身。 |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | 變更所有日期時間佔位符的可見性，包括母片投影片、版面配置投影片以及投影片本身。 |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | 設定所有標頭佔位符的文字，包括備註母片、備註投影片以及講義母片。 |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | 設定所有頁腳佔位符的文字，包括母片投影片、版面配置投影片以及投影片本身。 |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | 設定所有日期時間佔位符的文字，包括母片投影片、版面配置投影片以及投影片本身。 |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | 變更所有標題投影片以及第一個版面配置投影片的頁腳、日期時間與頁碼佔位符的可見性。 |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

變更所有標頭佔位符的可見性，包括備註母片、備註投影片以及講義母片。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使標頭佔位符可見，否則隱藏。 |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

變更所有頁腳佔位符的可見性，包括母片投影片、版面配置投影片以及投影片本身。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁腳佔位符可見，否則隱藏。 |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

變更所有頁碼佔位符的可見性，包括母片投影片、版面配置投影片以及投影片本身。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁碼佔位符可見，否則隱藏。 |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

變更所有日期時間佔位符的可見性，包括母片投影片、版面配置投影片以及投影片本身。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期時間佔位符可見，否則隱藏。 |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

設定所有標頭佔位符的文字，包括備註母片、備註投影片以及講義母片。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

設定所有頁腳佔位符的文字，包括母片投影片、版面配置投影片以及投影片本身。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

設定所有日期時間佔位符的文字，包括母片投影片、版面配置投影片以及投影片本身。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

變更所有標題投影片以及第一個版面配置投影片的頁腳、日期時間與頁碼佔位符的可見性。標題投影片 ─ 以第一個版面配置投影片為基礎的投影片（不論此第一個版面配置的類型）。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使佔位符可見，否則隱藏。 |