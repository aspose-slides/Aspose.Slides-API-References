---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示管理 layout slide footer、date-time、page number 佔位符以及所有子佔位符的行為。
type: docs
url: /zh-hant/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**所有已實作的介面：**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

表示管理 layout slide footer、date-time、page number 佔位符以及所有子佔位符的行為。子佔位符是指包含在依賴投影片中的佔位符。依賴投影片使用且依賴於 layout slide。
## 方法

| 方法 | 描述 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 變更 layout slide footer 佔位符及所有子 footer 佔位符的可見性。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 變更 layout slide page number 佔位符及所有子 page number 佔位符的可見性。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 變更 layout slide date-time 佔位符及所有子 date-time 佔位符的可見性。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 為 layout slide footer 佔位符及所有子 footer 佔位符設定文字。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 為 layout slide date-time 佔位符及所有子 date-time 佔位符設定文字。 |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

變更 layout slide footer 佔位符及所有子 footer 佔位符的可見性。子佔位符是指包含在依賴投影片中的佔位符。依賴投影片使用且依賴於 master slide。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使 footer 佔位符可見，否則 - 隱藏它們。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

變更 layout slide page number 佔位符及所有子 page number 佔位符的可見性。子佔位符是指包含在依賴投影片中的佔位符。依賴投影片使用且依賴於 layout slide。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使 page number 佔位符可見，否則 - 隱藏它們。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

變更 layout slide date-time 佔位符及所有子 date-time 佔位符的可見性。子佔位符是指包含在依賴投影片中的佔位符。依賴投影片使用且依賴於 layout slide。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使 date-time 佔位符可見，否則 - 隱藏它們。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

為 layout slide footer 佔位符及所有子 footer 佔位符設定文字。子佔位符是指包含在依賴投影片中的佔位符。依賴投影片使用且依賴於 layout slide。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

為 layout slide date-time 佔位符及所有子 date-time 佔位符設定文字。子佔位符是指包含在依賴投影片中的佔位符。依賴投影片使用且依賴於 layout slide。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |