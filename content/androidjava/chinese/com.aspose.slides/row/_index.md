---
title: Row
second_title: Aspose.Slides for Android via Java API 参考
description: 表示表格中的一行。
type: docs
url: /zh/com.aspose.slides/row/
---
**继承:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**已实现的所有接口:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

表示表格中的一行。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeight()](#getHeight--) | 返回行的高度。 |
| [getMinimalHeight()](#getMinimalHeight--) | 返回或设置行的最小可能高度。 |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | 返回或设置行的最小可能高度。 |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 将已定义的部分格式属性设置到所有行单元格的部分。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 将已定义的段落格式属性设置到所有行单元格的段落。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 将已定义的文本框格式属性设置到所有行单元格的文本框。 |
| [getRowFormat()](#getRowFormat--) | 返回包含此行格式属性的 RowFormat 对象。 |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


返回行的高度。只读 double.

**返回:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


返回或设置行的最小可能高度。读写 double.

**返回:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


返回或设置行的最小可能高度。读写 double.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


将已定义的部分格式属性设置到所有行单元格的部分。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 已设置必要属性的 IPortionFormat 对象。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


将已定义的段落格式属性设置到所有行单元格的段落。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 已设置必要属性的 IParagraphFormat 对象。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


将已定义的文本框格式属性设置到所有行单元格的文本框。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 已设置必要属性的 ITextFrameFormat 对象。 |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


返回包含此行格式属性的 RowFormat 对象。只读 [IRowFormat](../../com.aspose.slides/irowformat).

**返回:**
[IRowFormat](../../com.aspose.slides/irowformat)