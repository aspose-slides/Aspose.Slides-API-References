---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides for Android via Java API 參考
description: 表示管理器，負責保存簡報中所有頁腳、日期時間和頁碼佔位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/presentationheaderfootermanager/
---
**繼承:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)

**全部已實作介面:**
[com.aspose.slides.IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
```
public class PresentationHeaderFooterManager extends BaseHeaderFooterManager implements IPresentationHeaderFooterManager
```

表示管理器，負責保存簡報中所有頁腳、日期時間和頁碼佔位符的行為。

## 方法

| 方法 | 說明 |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | 變更所有標頭佔位符的可見性，包括備註母片、備註投影片和講義母片。 |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | 變更所有頁腳佔位符的可見性，包括母片投影片、版面投影片、投影片、備註母片、備註投影片和講義母片。 |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | 變更所有頁碼佔位符的可見性，包括母片投影片、版面投影片、投影片、備註母片、備註投影片和講義母片。 |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | 變更所有日期時間佔位符的可見性，包括母片投影片、版面投影片、投影片、備註母片、備註投影片和講義母片。 |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | 為所有標頭佔位符設定文字，包括備註母片、備註投影片和講義母片。 |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | 為所有頁腳佔位符設定文字，包括母片投影片、版面投影片、投影片、備註母片、備註投影片和講義母片。 |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | 為所有日期時間佔位符設定文字，包括母片投影片、版面投影片、投影片、備註母片、備註投影片和講義母片。 |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | 變更所有標題投影片以及第一個版面投影片的頁腳、日期時間和頁碼佔位符的可見性。 |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public final void setAllHeadersVisibility(boolean isVisible)
```

變更所有標頭佔位符的可見性，包括備註母片、備註投影片和講義母片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使標頭佔位符可見，否則 - 隱藏它們。 |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public final void setAllFootersVisibility(boolean isVisible)
```

變更所有頁腳佔位符的可見性，包括母片投影片、版面投影片、投影片、備註母片、備註投影片和講義母片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁腳佔位符可見，否則 - 隱藏它們。 |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public final void setAllSlideNumbersVisibility(boolean isVisible)
```

變更所有頁碼佔位符的可見性，包括母片投影片、版面投影片、投影片、備註母片、備註投影片和講義母片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁碼佔位符可見，否則 - 隱藏它們。 |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public final void setAllDateTimesVisibility(boolean isVisible)
```

變更所有日期時間佔位符的可見性，包括母片投影片、版面投影片、投影片、備註母片、備註投影片和講義母片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期時間佔位符可見，否則 - 隱藏它們。 |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public final void setAllHeadersText(String text)
```

為所有標頭佔位符設定文字，包括備註母片、備註投影片和講義母片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public final void setAllFootersText(String text)
```

為所有頁腳佔位符設定文字，包括母片投影片、版面投影片、投影片、備註母片、備註投影片和講義母片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public final void setAllDateTimesText(String text)
```

為所有日期時間佔位符設定文字，包括母片投影片、版面投影片、投影片、備註母片、備註投影片和講義母片。

**參數:**
 | 參數 | 類型 | 說明 |
 | --- | --- | --- |
 | text | java.lang.String | 要設定的文字。 |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public final void setVisibilityOnAllTitleSlides(boolean isVisible)
```

變更所有標題投影片以及第一個版面投影片的頁腳、日期時間和頁碼佔位符的可見性。標題投影片 \\u2013 基於第一個版面投影片的投影片（不論此第一個版面的類型）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使佔位符可見，否則 - 隱藏它們。 |