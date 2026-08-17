---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides Java API 参考
description: 表示管理器，负责布局幻灯片页脚、日期时间、页码占位符以及所有子占位符的行为。
type: docs
url: /zh/com.aspose.slides/layoutslideheaderfootermanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

表示管理器，负责布局幻灯片页脚、日期时间、页码占位符及所有子占位符的行为。子占位符指的是包含在依赖幻灯片上的占位符。依赖幻灯片使用并依赖于布局幻灯片。

## Methods

| Method | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 更改布局幻灯片页脚占位符以及所有子页脚占位符的可见性。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 更改布局幻灯片页码占位符以及所有子页码占位符的可见性。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 更改布局幻灯片日期时间占位符以及所有子日期时间占位符的可见性。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 设置布局幻灯片页脚占位符及所有子页脚占位符的文本。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 设置布局幻灯片日期时间占位符及所有子日期时间占位符的文本。 |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

更改布局幻灯片页脚占位符以及所有子页脚占位符的可见性。子占位符指的是包含在依赖幻灯片上的占位符。依赖幻灯片使用并依赖于母版幻灯片。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - 使页脚占位符可见，otherwise - 隐藏它们。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

更改布局幻灯片页码占位符以及所有子页码占位符的可见性。子占位符指的是包含在依赖幻灯片上的占位符。依赖幻灯片使用并依赖于布局幻灯片。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - 使页码占位符可见，otherwise - 隐藏它们。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

更改布局幻灯片日期时间占位符以及所有子日期时间占位符的可见性。子占位符指的是包含在依赖幻灯片上的占位符。依赖幻灯片使用并依赖于布局幻灯片。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - 使日期时间占位符可见，otherwise - 隐藏它们。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

设置布局幻灯片页脚占位符及所有子页脚占位符的文本。子占位符指的是包含在依赖幻灯片上的占位符。依赖幻灯片使用并依赖于布局幻灯片。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

设置布局幻灯片日期时间占位符及所有子日期时间占位符的文本。子占位符指的是包含在依赖幻灯片上的占位符。依赖幻灯片使用并依赖于布局幻灯片。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |