---
title: ILineFormat
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示一条线的格式。
type: docs
url: /zh/com.aspose.slides/ilineformat/
---
**所有实现的接口：**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

表示一条线的格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | 如果线格式未定义（刚创建时的默认值），返回 true。 |
| [getFillFormat()](#getFillFormat--) | 返回线的填充格式。 |
| [getSketchFormat()](#getSketchFormat--) | 返回线的草图格式。 |
| [getWidth()](#getWidth--) | 返回或设置线的宽度。 |
| [setWidth(double value)](#setWidth-double-) | 返回或设置线的宽度。 |
| [getDashStyle()](#getDashStyle--) | 返回或设置线的虚线样式。 |
| [setDashStyle(byte value)](#setDashStyle-byte-) | 返回或设置线的虚线样式。 |
| [getCustomDashPattern()](#getCustomDashPattern--) | 返回或设置自定义虚线模式。 |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | 返回或设置自定义虚线模式。 |
| [getCapStyle()](#getCapStyle--) | 返回或设置线的端帽样式。 |
| [setCapStyle(byte value)](#setCapStyle-byte-) | 返回或设置线的端帽样式。 |
| [getStyle()](#getStyle--) | 返回或设置线的样式。 |
| [setStyle(byte value)](#setStyle-byte-) | 返回或设置线的样式。 |
| [getAlignment()](#getAlignment--) | 返回或设置线的对齐方式。 |
| [setAlignment(byte value)](#setAlignment-byte-) | 返回或设置线的对齐方式。 |
| [getJoinStyle()](#getJoinStyle--) | 返回或设置线的接合样式。 |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | 返回或设置线的接合样式。 |
| [getMiterLimit()](#getMiterLimit--) | 返回或设置线的斜接限制。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 返回或设置线的斜接限制。 |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | 返回或设置线起点的箭头样式。 |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | 返回或设置线起点的箭头样式。 |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | 返回或设置线终点的箭头样式。 |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | 返回或设置线终点的箭头样式。 |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | 返回或设置线起点的箭头宽度。 |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | 返回或设置线起点的箭头宽度。 |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | 返回或设置线终点的箭头宽度。 |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | 返回或设置线终点的箭头宽度。 |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | 返回或设置线起点的箭头长度。 |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | 返回或设置线起点的箭头长度。 |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | 返回或设置线终点的箭头长度。 |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | 返回或设置线终点的箭头长度。 |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | 确定两个 LineFormat 实例是否相等。 |
| [getEffective()](#getEffective--) | 获取已应用继承的有效线格式化数据。 |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

只读 boolean。

**返回:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

只读 [ILineFillFormat](../../com.aspose.slides/ilinefillformat)，返回线的填充格式。

**返回:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

只读 [ISketchFormat](../../com.aspose.slides/isketchformat)，返回线的草图格式。

**返回:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

读写 double，返回或设置线的宽度。

**返回:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

读写 double，返回或设置线的宽度。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

读写 [LineDashStyle](../../com.aspose.slides/linedashstyle)，返回或设置线的虚线样式。

**返回:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

读写 [LineDashStyle](../../com.aspose.slides/linedashstyle)，返回或设置线的虚线样式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

读写 float[]，返回或设置自定义虚线模式。

**返回:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

读写 float[]，返回或设置自定义虚线模式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

读写 [LineCapStyle](../../com.aspose.slides/linecapstyle)，返回或设置线的端帽样式。

**返回:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

读写 [LineCapStyle](../../com.aspose.slides/linecapstyle)，返回或设置线的端帽样式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

读写 [LineStyle](../../com.aspose.slides/linestyle)，返回或设置线的样式。

**返回:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

读写 [LineStyle](../../com.aspose.slides/linestyle)，返回或设置线的样式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

读写 [LineAlignment](../../com.aspose.slides/linealignment)，返回或设置线的对齐方式。

**返回:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

读写 [LineAlignment](../../com.aspose.slides/linealignment)，返回或设置线的对齐方式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

读写 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)，返回或设置线的接合样式。

**返回:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

读写 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)，返回或设置线的接合样式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

读写 float，返回或设置线的斜接限制。

**返回:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

读写 float，返回或设置线的斜接限制。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

读写 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)，返回或设置线起点的箭头样式。

**返回:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

读写 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)，返回或设置线起点的箭头样式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

读写 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)，返回或设置线终点的箭头样式。

**返回:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

读写 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)，返回或设置线终点的箭头样式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

读写 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)，返回或设置线起点的箭头宽度。

**返回:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

读写 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)，返回或设置线起点的箭头宽度。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

读写 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)，返回或设置线终点的箭头宽度。

**返回:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

读写 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)，返回或设置线终点的箭头宽度。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

读写 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)，返回或设置线起点的箭头长度。

**返回:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

读写 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)，返回或设置线起点的箭头长度。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

读写 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)，返回或设置线终点的箭头长度。

**返回:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

读写 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)，返回或设置线终点的箭头长度。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

确定两个 LineFormat 实例是否相等。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | 要与当前 LineFormat 比较的 LineFormat。 |

**返回:**
boolean - **true** 表示指定的 LineFormat 与当前 LineFormat 相等；否则 **false**。
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

获取已应用继承的有效线格式化数据。

**返回:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - 一个 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。