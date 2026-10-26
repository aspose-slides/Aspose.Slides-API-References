---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides for Android via Java API 参考
description: 表示管理器，负责母版幻灯片页脚、日期时间、页码占位符及所有子占位符的行为。
type: docs
url: /zh/com.aspose.slides/masterslideheaderfootermanager/
---
**继承:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**所有实现的接口:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

表示管理器，控制母版幻灯片页脚、日期时间、页码占位符以及所有子占位符的行为。子占位符指的是包含在依赖布局幻灯片和依赖幻灯片上的占位符。依赖布局幻灯片和幻灯片使用并依赖于母版幻灯片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 更改母版幻灯片页脚占位符以及所有子页脚占位符的可见性。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 更改母版幻灯片页码占位符以及所有子页码占位符的可见性。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 更改母版幻灯片日期时间占位符以及所有子日期时间占位符的可见性。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 为母版幻灯片页脚占位符以及所有子页脚占位符设置文本。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 为母版幻灯片日期时间占位符以及所有子日期时间占位符设置文本。 |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

更改母版幻灯片页脚占位符以及所有子页脚占位符的可见性。子占位符指的是包含在依赖布局幻灯片和依赖幻灯片上的占位符。依赖布局幻灯片和幻灯片使用并依赖于母版幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页脚占位符可见，其他情况 - 隐藏它们。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

更改母版幻灯片页码占位符以及所有子页码占位符的可见性。子占位符指的是包含在依赖布局幻灯片和依赖幻灯片上的占位符。依赖布局幻灯片和幻灯片使用并依赖于母版幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页码占位符可见，其他情况 - 隐藏它们。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

更改母版幻灯片日期时间占位符以及所有子日期时间占位符的可见性。子占位符指的是包含在依赖布局幻灯片和依赖幻灯片上的占位符。依赖布局幻灯片和幻灯片使用并依赖于母版幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期时间占位符可见，其他情况 - 隐藏它们。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

为母版幻灯片页脚占位符以及所有子页脚占位符设置文本。子占位符指的是包含在依赖布局幻灯片和依赖幻灯片上的占位符。依赖布局幻灯片和幻灯片使用并依赖于母版幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

为母版幻灯片日期时间占位符以及所有子日期时间占位符设置文本。子占位符指的是包含在依赖布局幻灯片和依赖幻灯片上的占位符。依赖布局幻灯片和幻灯片使用并依赖于母版幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |