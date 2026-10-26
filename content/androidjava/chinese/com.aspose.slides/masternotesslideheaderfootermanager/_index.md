---
title: MasterNotesSlideHeaderFooterManager
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示管理器，负责维护母版备注幻灯片页脚、日期时间、页码占位符以及所有子占位符的行为。
type: docs
url: /zh/com.aspose.slides/masternotesslideheaderfootermanager/
---
**继承:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**所有已实现的接口:**
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

表示管理器，负责保持母版备注幻灯片的页脚、日期时间、页码占位符以及所有子占位符的行为。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | 更改母版备注幻灯片标题占位符以及所有子标题占位符的可见性。 |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | 将文本设置到母版备注幻灯片标题占位符以及所有子标题占位符。 |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 更改母版幻灯片页脚占位符以及所有子页脚占位符的可见性。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 更改母版幻灯片页码占位符以及所有子页码占位符的可见性。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 更改母版幻灯片日期时间占位符以及所有子日期时间占位符的可见性。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 将文本设置到母版幻灯片页脚占位符以及所有子页脚占位符。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 将文本设置到母版幻灯片日期时间占位符以及所有子日期时间占位符。 |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

更改母版备注幻灯片标题占位符以及所有子标题占位符的可见性。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使标题占位符可见，false - 隐藏它们。 |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

将文本设置到母版备注幻灯片标题占位符以及所有子标题占位符。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

更改母版幻灯片页脚占位符以及所有子页脚占位符的可见性。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页脚占位符可见，false - 隐藏它们。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

更改母版幻灯片页码占位符以及所有子页码占位符的可见性。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页码占位符可见，false - 隐藏它们。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

更改母版幻灯片日期时间占位符以及所有子日期时间占位符的可见性。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期时间占位符可见，false - 隐藏它们。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

将文本设置到母版幻灯片页脚占位符以及所有子页脚占位符。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

将文本设置到母版幻灯片日期时间占位符以及所有子日期时间占位符。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |