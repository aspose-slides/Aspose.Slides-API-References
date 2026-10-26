---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides for Java API 參考
description: 代表管理器，保存簡報中所有頁腳、日期時間和頁碼佔位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/ipresentationheaderfootermanager/
---
**所有已實作的介面:**  
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

代表管理器，負責保存簡報中所有頁腳、日期時間和頁碼佔位符的行為。

## 方法

| 方法 | 描述 |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | 更改所有標題佔位符的可見性，包括註解母片、註解投影片以及講義母片。 |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | 更改所有頁腳佔位符的可見性，包括母片投影片、版面配置投影片以及普通投影片。 |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | 更改所有頁碼佔位符的可見性，包括母片投影片、版面配置投影片以及普通投影片。 |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | 更改所有日期時間佔位符的可見性，包括母片投影片、版面配置投影片以及普通投影片。 |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | 設定文字至所有標題佔位符，包括註解母片、註解投影片以及講義母片。 |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | 設定文字至所有頁腳佔位符，包括母片投影片、版面配置投影片以及普通投影片。 |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | 設定文字至所有日期時間佔位符，包括母片投影片、版面配置投影片以及普通投影片。 |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | 更改所有標題投影片及第一個版面配置投影片的頁腳、日期時間與頁碼佔位符的可見性。 |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

更改所有標題佔位符的可見性，包括註解母片、註解投影片以及講義母片。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使標題佔位符可見，否則隱藏它們。 |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

更改所有頁腳佔位符的可見性，包括母片投影片、版面配置投影片以及普通投影片。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁腳佔位符可見，否則隱藏它們。 |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

更改所有頁碼佔位符的可見性，包括母片投影片、版面配置投影片以及普通投影片。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁碼佔位符可見，否則隱藏它們。 |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

更改所有日期時間佔位符的可見性，包括母片投影片、版面配置投影片以及普通投影片。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期時間佔位符可見，否則隱藏它們。 |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

設定文字至所有標題佔位符，包括註解母片、註解投影片以及講義母片。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

設定文字至所有頁腳佔位符，包括母片投影片、版面配置投影片以及普通投影片。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

設定文字至所有日期時間佔位符，包括母片投影片、版面配置投影片以及普通投影片。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

更改所有標題投影片及第一個版面配置投影片的頁腳、日期時間與頁碼佔位符的可見性。標題投影片 \\u2013 基於第一個版面配置投影片的投影片（不論此第一個版面配置的類型）。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使佔位符可見，否則隱藏它們。 |