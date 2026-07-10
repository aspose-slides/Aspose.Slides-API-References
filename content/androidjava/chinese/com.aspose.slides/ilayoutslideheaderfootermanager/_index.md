---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示管理器，负责布局幻灯片页脚、日期时间、页码占位符及所有子占位符的行为。
type: docs
url: /zh/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**所有实现的接口：**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

表示管理器，负责布局幻灯片页脚、日期时间、页码占位符以及所有子占位符的行为。子占位符指的是包含在依赖幻灯片中的占位符。依赖幻灯片使用并依赖于布局幻灯片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 更改布局幻灯片页脚占位符及所有子页脚占位符的可见性。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 更改布局幻灯片页码占位符及所有子页码占位符的可见性。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 更改布局幻灯片日期时间占位符及所有子日期时间占位符的可见性。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 为布局幻灯片页脚占位符及所有子页脚占位符设置文本。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 为布局幻灯片日期时间占位符及所有子日期时间占位符设置文本。 |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

更改布局幻灯片页脚占位符及所有子页脚占位符的可见性。子占位符指的是包含在依赖幻灯片中的占位符。依赖幻灯片使用并依赖于母版幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页脚占位符可见，false - 隐藏它们。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

更改布局幻灯片页码占位符及所有子页码占位符的可见性。子占位符指的是包含在依赖幻灯片中的占位符。依赖幻灯片使用并依赖于布局幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页码占位符可见，false - 隐藏它们。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

更改布局幻灯片日期时间占位符及所有子日期时间占位符的可见性。子占位符指的是包含在依赖幻灯片中的占位符。依赖幻灯片使用并依赖于布局幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期时间占位符可见，false - 隐藏它们。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

为布局幻灯片页脚占位符及所有子页脚占位符设置文本。子占位符指的是包含在依赖幻灯片中的占位符。依赖幻灯片使用并依赖于布局幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

为布局幻灯片日期时间占位符及所有子日期时间占位符设置文本。子占位符指的是包含在依赖幻灯片中的占位符。依赖幻灯片使用并依赖于布局幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |