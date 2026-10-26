---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides for Android via Java API 參考
description: 代表管理器，負責維持母片投影片頁腳、日期時間、頁碼佔位符以及所有子佔位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/masterslideheaderfootermanager/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**所有已實作的介面:**  
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

此管理器代表持有母片投影片頁腳、日期時間、頁碼佔位符及所有子佔位符的行為。子佔位符指的是位於依賴的版面配置投影片和依賴投影片中的佔位符。依賴的版面配置投影片和投影片使用且依賴於母片投影片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 變更母片投影片頁腳佔位符及所有子頁腳佔位符的可見性。子佔位符指的是位於依賴的版面配置投影片和依賴投影片中的佔位符。依賴的版面配置投影片和投影片使用且依賴於母片投影片。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 變更母片投影片頁碼佔位符及所有子頁碼佔位符的可見性。子佔位符指的是位於依賴的版面配置投影片和依賴投影片中的佔位符。依賴的版面配置投影片和投影片使用且依賴於母片投影片。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 變更母片投影片日期時間佔位符及所有子日期時間佔位符的可見性。子佔位符指的是位於依賴的版面配置投影片和依賴投影片中的佔位符。依賴的版面配置投影片和投影片使用且依賴於母片投影片。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 設定文字至母片投影片頁腳佔位符及所有子頁腳佔位符。子佔位符指的是位於依賴的版面配置投影片和依賴投影片中的佔位符。依賴的版面配置投影片和投影片使用且依賴於母片投影片。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 設定文字至母片投影片日期時間佔位符及所有子日期時間佔位符。子佔位符指的是位於依賴的版面配置投影片和依賴投影片中的佔位符。依賴的版面配置投影片和投影片使用且依賴於母片投影片。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

變更母片投影片頁腳佔位符及所有子頁腳佔位符的可見性。子佔位符指的是位於依賴的版面配置投影片和依賴投影片中的佔位符。依賴的版面配置投影片和投影片使用且依賴於母片投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁腳佔位符可見，否則隱藏它們。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

變更母片投影片頁碼佔位符及所有子頁碼佔位符的可見性。子佔位符指的是位於依賴的版面配置投影片和依賴投影片中的佔位符。依賴的版面配置投影片和投影片使用且依賴於母片投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁碼佔位符可見，否則隱藏它們。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

變更母片投影片日期時間佔位符及所有子日期時間佔位符的可見性。子佔位符指的是位於依賴的版面配置投影片和依賴投影片中的佔位符。依賴的版面配置投影片和投影片使用且依賴於母片投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期時間佔位符可見，否則隱藏它們。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

設定文字至母片投影片頁腳佔位符及所有子頁腳佔位符。子佔位符指的是位於依賴的版面配置投影片和依賴投影片中的佔位符。依賴的版面配置投影片和投影片使用且依賴於母片投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

設定文字至母片投影片日期時間佔位符及所有子日期時間佔位符。子佔位符指的是位於依賴的版面配置投影片和依賴投影片中的佔位符。依賴的版面配置投影片和投影片使用且依賴於母片投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |