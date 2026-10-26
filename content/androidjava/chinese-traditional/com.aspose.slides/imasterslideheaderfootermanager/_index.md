---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示管理員，負責掌管母片投影片的頁腳、日期時間、頁碼佔位符以及所有子佔位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/imasterslideheaderfootermanager/
---
**所有已實作的介面：**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

表示管理員，負責掌管母片投影片的頁腳、日期時間、頁碼佔位符以及所有子佔位符的行為。子佔位符表示佔位符位於相依版面投影片和相依投影片上。相依版面投影片和投影片使用並依賴母片投影片。

## 方法

| 方法 | 說明 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 變更母片投影片頁腳佔位符及所有子頁腳佔位符的可見性。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 變更母片投影片頁碼佔位符及所有子頁碼佔位符的可見性。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 變更母片投影片日期時間佔位符及所有子日期時間佔位符的可見性。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 將文字設定至母片投影片頁腳佔位符及所有子頁腳佔位符。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 將文字設定至母片投影片日期時間佔位符及所有子日期時間佔位符。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

變更母片投影片頁腳佔位符及所有子頁腳佔位符的可見性。子佔位符表示佔位符位於相依版面投影片和相依投影片上。相依版面投影片和投影片使用並依賴母片投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁腳佔位符可見，否則 - 隱藏它們。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

變更母片投影片頁碼佔位符及所有子頁碼佔位符的可見性。子佔位符表示佔位符位於相依版面投影片和相依投影片上。相依版面投影片和投影片使用並依賴母片投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁號佔位符可見，否則 - 隱藏它們。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

變更母片投影片日期時間佔位符及所有子日期時間佔位符的可見性。子佔位符表示佔位符位於相依版面投影片和相依投影片上。相依版面投影片和投影片使用並依賴母片投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期時間佔位符可見，否則 - 隱藏它們。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

將文字設定至母片投影片頁腳佔位符及所有子頁腳佔位符。子佔位符表示佔位符位於相依版面投影片和相依投影片上。相依版面投影片和投影片使用並依賴母片投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

將文字設定至母片投影片日期時間佔位符及所有子日期時間佔位符。子佔位符表示佔位符位於相依版面投影片和相依投影片上。相依版面投影片和投影片使用並依賴母片投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |