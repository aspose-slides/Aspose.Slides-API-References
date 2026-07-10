---
title: ILineFormatEffectiveData
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 不可变对象，包含有效的线条格式属性。
type: docs
url: /zh/com.aspose.slides/ilineformateffectivedata/
---
**所有已实现的接口：**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

不可变对象，包含有效的线条格式属性。

--------------------

此接口与 [ILineFormat](../../com.aspose.slides/ilineformat) 接口一起使用，以返回应用继承后的有效格式值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 返回线的填充格式。 |
| [getSketchFormat()](#getSketchFormat--) | 返回线的草图格式。 |
| [getWidth()](#getWidth--) | 返回线的宽度。 |
| [getDashStyle()](#getDashStyle--) | 返回线的虚线样式。 |
| [getCustomDashPattern()](#getCustomDashPattern--) | 返回自定义虚线模式。 |
| [getCapStyle()](#getCapStyle--) | 返回线的端点样式。 |
| [getStyle()](#getStyle--) | 返回线的样式。 |
| [getAlignment()](#getAlignment--) | 返回线的对齐方式。 |
| [getJoinStyle()](#getJoinStyle--) | 返回线的连接样式。 |
| [getMiterLimit()](#getMiterLimit--) | 返回线的斜接限制。 |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | 返回线起始端的箭头样式。 |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | 返回线结束端的箭头样式。 |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | 返回线起始端的箭头宽度。 |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | 返回线结束端的箭头宽度。 |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | 返回线起始端的箭头长度。 |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | 返回线结束端的箭头长度。 |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | 判断两个 ILineFormatEffectiveData 实例是否相等。 |

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

返回线的填充格式。只读 [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)。

**返回：**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

返回线的草图格式。只读 [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)。

**返回：**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

返回线的宽度。只读 double。

**返回：**
double

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

返回线的虚线样式。只读 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**返回：**
byte

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

返回自定义虚线模式。只读 float[]。

**返回：**
float[]

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

返回线的端点样式。只读 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**返回：**
byte

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

返回线的样式。只读 [LineStyle](../../com.aspose.slides/linestyle)。

**返回：**
byte

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

返回线的对齐方式。只读 [LineAlignment](../../com.aspose.slides/linealignment)。

**返回：**
byte

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

返回线的连接样式。只读 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**返回：**
byte

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

返回线的斜接限制。只读 float。

**返回：**
float

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

返回线起始端的箭头样式。只读 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**返回：**
byte

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

返回线结束端的箭头样式。只读 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**返回：**
byte

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

返回线起始端的箭头宽度。只读 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**返回：**
byte

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

返回线结束端的箭头宽度。只读 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**返回：**
byte

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

返回线起始端的箭头长度。只读 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**返回：**
byte

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

返回线结束端的箭头长度。只读 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**返回：**
byte

### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

判断两个 ILineFormatEffectiveData 实例是否相等。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | 与当前 ILineFormatEffectiveData 比较的 ILineFormatEffectiveData。 |

**返回：**
boolean - **true** if the specified ILineFormatEffectiveData is equal to the current ILineFormatEffectiveData; otherwise, **false**.