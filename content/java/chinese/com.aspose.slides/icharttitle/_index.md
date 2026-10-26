---
title: IChartTitle
second_title: Aspose.Slides Java API 参考
description: 表示图表标题属性。
type: docs
url: /zh/com.aspose.slides/icharttitle/
---
**所有实现的接口：**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

表示图表标题属性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getOverlay()](#getOverlay--) | 确定是否允许其他图表元素覆盖标题。 |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 确定是否允许其他图表元素覆盖标题。 |
| [getFormat()](#getFormat--) | 返回标题的填充、线条和效果样式。 |

### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

确定是否允许其他图表元素覆盖标题。 可读写布尔值。

**返回：**
boolean

### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

确定是否允许其他图表元素覆盖标题。 可读写布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

返回标题的填充、线条和效果样式。 只读 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)