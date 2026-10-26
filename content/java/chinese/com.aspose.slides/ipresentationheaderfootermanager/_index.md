---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides for Java API 参考
description: 表示管理器，负责演示文稿中所有页脚、日期时间和页码占位符的行为。
type: docs
url: /zh/com.aspose.slides/ipresentationheaderfootermanager/
---
**已实现的接口:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

表示管理器，负责演示文稿中所有页脚、日期时间和页码占位符的行为。
## 方法

| 方法 | 描述 |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | 更改所有页眉占位符的可见性，包括备注母版、备注幻灯片和讲义母版。 |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | 更改所有页脚占位符的可见性，包括母版幻灯片、布局幻灯片和幻灯片。 |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | 更改所有页码占位符的可见性，包括母版幻灯片、布局幻灯片和幻灯片。 |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | 更改所有日期时间占位符的可见性，包括母版幻灯片、布局幻灯片和幻灯片。 |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | 设置所有页眉占位符的文本，包括备注母版、备注幻灯片和讲义母版。 |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | 设置所有页脚占位符的文本，包括母版幻灯片、布局幻灯片和幻灯片。 |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | 设置所有日期时间占位符的文本，包括母版幻灯片、布局幻灯片和幻灯片。 |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | 更改所有标题幻灯片以及第一布局幻灯片的页脚、日期时间和页码占位符的可见性。 |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

更改所有页眉占位符的可见性，包括备注母版、备注幻灯片和讲义母版。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页眉占位符可见，否则 - 隐藏它们。 |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

更改所有页脚占位符的可见性，包括母版幻灯片、布局幻灯片和幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页脚占位符可见，否则 - 隐藏它们。 |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

更改所有页码占位符的可见性，包括母版幻灯片、布局幻灯片和幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页码占位符可见，否则 - 隐藏它们。 |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

更改所有日期时间占位符的可见性，包括母版幻灯片、布局幻灯片和幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期时间占位符可见，否则 - 隐藏它们。 |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

设置所有页眉占位符的文本，包括备注母版、备注幻灯片和讲义母版。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

设置所有页脚占位符的文本，包括母版幻灯片、布局幻灯片和幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

设置所有日期时间占位符的文本，包括母版幻灯片、布局幻灯片和幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

更改所有标题幻灯片以及第一布局幻灯片的页脚、日期时间和页码占位符的可见性。标题幻灯片 – 基于第一布局幻灯片的幻灯片（不论该第一布局的类型）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使占位符可见，否则 - 隐藏它们。 |