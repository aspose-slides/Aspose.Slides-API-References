---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides for Java API 參考
description: 此管理器代表佈局投影片頁腳、日期時間、頁碼占位符以及所有子占位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**所有已實作的介面：**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

此管理器代表了布局投影片頁腳、日期時間、頁碼占位符以及所有子占位符的行為。子占位符指的是包含在依賴投影片上的占位符。依賴投影片使用且依賴於布局投影片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 變更布局投影片頁腳占位符及所有子頁腳占位符的可見性。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 變更布局投影片頁碼占位符及所有子頁碼占位符的可見性。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 變更布局投影片日期時間占位符及所有子日期時間占位符的可見性。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 將文字設定至布局投影片頁腳占位符及所有子頁腳占位符。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 將文字設定至布局投影片日期時間占位符及所有子日期時間占位符。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

變更布局投影片頁腳占位符及所有子頁腳占位符的可見性。子占位符指的是包含在依賴投影片上的占位符。依賴投影片使用且依賴於母片。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁腳占位符可見，否則 - 隱藏它們。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

變更布局投影片頁碼占位符及所有子頁碼占位符的可見性。子占位符指的是包含在依賴投影片上的占位符。依賴投影片使用且依賴於布局投影片。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使頁碼占位符可見，否則 - 隱藏它們。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

變更布局投影片日期時間占位符及所有子日期時間占位符的可見性。子占位符指的是包含在依賴投影片上的占位符。依賴投影片使用且依賴於布局投影片。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期時間占位符可見，否則 - 隱藏它們。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

將文字設定至布局投影片頁腳占位符及所有子頁腳占位符。子占位符指的是包含在依賴投影片上的占位符。依賴投影片使用且依賴於布局投影片。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

將文字設定至布局投影片日期時間占位符及所有子日期時間占位符。子占位符指的是包含在依賴投影片上的占位符。依賴投影片使用且依賴於布局投影片。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |