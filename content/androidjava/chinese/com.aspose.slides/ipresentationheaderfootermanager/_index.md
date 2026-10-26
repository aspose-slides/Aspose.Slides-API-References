---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides for Android via Java API 参考
description: 表示管理器，负责持有演示文稿中所有页脚、日期时间和页码占位符的行为。
type: docs
url: /zh/com.aspose.slides/ipresentationheaderfootermanager/
---
**所有已实现的接口:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

表示管理器，负责持有演示文稿中所有页脚、日期时间和页码占位符的行为。
## 方法

| 方法 | 描述 |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | 更改所有页眉占位符的可见性，包括备注母版、备注幻灯片和讲义母版。 |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | 更改所有页脚占位符的可见性，包括母版幻灯片、布局幻灯片和普通幻灯片。 |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | 更改所有页码占位符的可见性，包括母版幻灯片、布局幻灯片和普通幻灯片。 |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | 更改所有日期时间占位符的可见性，包括母版幻灯片、布局幻灯片和普通幻灯片。 |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | 为所有页眉占位符设置文本，包括备注母版、备注幻灯片和讲义母版。 |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | 为所有页脚占位符设置文本，包括母版幻灯片、布局幻灯片和普通幻灯片。 |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | 为所有日期时间占位符设置文本，包括母版幻灯片、布局幻灯片和普通幻灯片。 |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | 更改所有标题幻灯片以及首个布局幻灯片的页脚、日期时间和页码占位符的可见性。 |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

更改所有页眉占位符的可见性，包括备注母版、备注幻灯片和讲义母版。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页眉占位符可见，false - 隐藏它们。 |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

更改所有页脚占位符的可见性，包括母版幻灯片、布局幻灯片和普通幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页脚占位符可见，false - 隐藏它们。 |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

更改所有页码占位符的可见性，包括母版幻灯片、布局幻灯片和普通幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使页码占位符可见，false - 隐藏它们。 |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

更改所有日期时间占位符的可见性，包括母版幻灯片、布局幻灯片和普通幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使日期时间占位符可见，false - 隐藏它们。 |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

为所有页眉占位符设置文本，包括备注母版、备注幻灯片和讲义母版。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

为所有页脚占位符设置文本，包括母版幻灯片、布局幻灯片和普通幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

为所有日期时间占位符设置文本，包括母版幻灯片、布局幻灯片和普通幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要设置的文本。 |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

更改所有标题幻灯片以及首个布局幻灯片的页脚、日期时间和页码占位符的可见性。标题幻灯片 – 基于首个布局幻灯片的幻灯片（无论该布局的类型如何）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使占位符可见，false - 隐藏它们。 |