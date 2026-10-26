---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides 适用于 Android 的 Java API 参考
description: 表示管理器，负责维护母版备注幻灯片的页脚、日期时间、页码占位符以及所有子占位符的行为。
type: docs
url: /zh/com.aspose.slides/imasternotesslideheaderfootermanager/
---

**所有实现的接口:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

表示管理器，负责维护母版备注幻灯片的页脚、日期时间、页码占位符以及所有子占位符的行为。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | 更改母版备注幻灯片的标题占位符及所有子标题占位符的可见性。 |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | 为母版备注幻灯片的标题占位符及所有子标题占位符设置文本。 |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 更改母版备注幻灯片的页脚占位符及所有子页脚占位符的可见性。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 更改母版备注幻灯片的页码占位符及所有子页码占位符的可见性。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 更改母版备注幻灯片的日期时间占位符及所有子日期时间占位符的可见性。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 为母版备注幻灯片的页脚占位符及所有子页脚占位符设置文本。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 为母版备注幻灯片的日期时间占位符及所有子日期时间占位符设置文本。 |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

更改母版备注幻灯片的标题占位符及所有子标题占位符的可见性。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使标题占位符可见，false - 隐藏它们。 |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

为母版备注幻灯片的标题占位符及所有子标题占位符设置文本。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

更改母版备注幻灯片的页脚占位符及所有子页脚占位符的可见性。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页脚占位符可见，false - 隐藏它们。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

更改母版备注幻灯片的页码占位符及所有子页码占位符的可见性。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页码占位符可见，false - 隐藏它们。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

更改母版备注幻灯片的日期时间占位符及所有子日期时间占位符的可见性。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期时间占位符可见，false - 隐藏它们。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

为母版备注幻灯片的页脚占位符及所有子页脚占位符设置文本。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

为母版备注幻灯片的日期时间占位符及所有子日期时间占位符设置文本。子占位符指的是包含在依赖的备注幻灯片中的占位符。依赖的备注幻灯片使用并依赖于母版备注幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |