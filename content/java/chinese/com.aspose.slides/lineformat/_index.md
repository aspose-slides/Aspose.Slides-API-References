---
title: LineFormat
second_title: Aspose.Slides for Java API 参考
description: 表示线的格式。
type: docs
url: /zh/com.aspose.slides/lineformat/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**已实现的接口:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

表示线的格式。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | 如果线格式未定义（刚创建时的默认状态），返回 true。 |
| [getFillFormat()](#getFillFormat--) | 返回线的填充格式。 |
| [getSketchFormat()](#getSketchFormat--) | 返回线的草图格式。 |
| [getWidth()](#getWidth--) | 返回或设置线的宽度。 |
| [setWidth(double value)](#setWidth-double-) | 返回或设置线的宽度。 |
| [getDashStyle()](#getDashStyle--) | 返回或设置线的虚线样式。 |
| [setDashStyle(byte value)](#setDashStyle-byte-) | 返回或设置线的虚线样式。 |
| [getCustomDashPattern()](#getCustomDashPattern--) | 返回或设置自定义虚线模式。 |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | 返回或设置自定义虚线模式。 |
| [getCapStyle()](#getCapStyle--) | 返回或设置线的端点样式。 |
| [setCapStyle(byte value)](#setCapStyle-byte-) | 返回或设置线的端点样式。 |
| [getStyle()](#getStyle--) | 返回或设置线的样式。 |
| [setStyle(byte value)](#setStyle-byte-) | 返回或设置线的样式。 |
| [getAlignment()](#getAlignment--) | 返回或设置线的对齐方式。 |
| [setAlignment(byte value)](#setAlignment-byte-) | 返回或设置线的对齐方式。 |
| [getJoinStyle()](#getJoinStyle--) | 返回或设置线的连接方式。 |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | 返回或设置线的连接方式。 |
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
| [getEffective()](#getEffective--) | 获取应用继承后的有效线格式化数据。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**Returns:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

与指定对象比较。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

如果线格式未定义（刚创建时的默认状态），返回 true。只读 boolean 。

**Returns:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

返回线的填充格式。只读 [ILineFillFormat](../../com.aspose.slides/ilinefillformat)。

**Returns:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

返回线的草图格式。只读 [ILineFillFormat](../../com.aspose.slides/ilinefillformat)。

**Returns:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

返回或设置线的宽度。可读写 double 。

**Returns:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

返回或设置线的宽度。可读写 double 。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

返回或设置线的虚线样式。可读写 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**Returns:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

返回或设置线的虚线样式。可读写 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

返回或设置自定义虚线模式。可读写 float[] 。

**Returns:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

返回或设置自定义虚线模式。可读写 float[] 。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

返回或设置线的端点样式。可读写 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**Returns:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

返回或设置线的端点样式。可读写 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

返回或设置线的样式。可读写 [LineStyle](../../com.aspose.slides/linestyle)。

**Returns:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

返回或设置线的样式。可读写 [LineStyle](../../com.aspose.slides/linestyle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

返回或设置线的对齐方式。可读写 [LineAlignment](../../com.aspose.slides/linealignment)。

**Returns:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

返回或设置线的对齐方式。可读写 [LineAlignment](../../com.aspose.slides/linealignment)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

返回或设置线的连接方式。可读写 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**Returns:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

返回或设置线的连接方式。可读写 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

返回或设置线的斜接限制。可读写 float 。

**Returns:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

返回或设置线的斜接限制。可读写 float 。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

返回或设置线起点的箭头样式。可读写 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**Returns:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

返回或设置线起点的箭头样式。可读写 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

返回或设置线终点的箭头样式。可读写 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**Returns:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

返回或设置线终点的箭头样式。可读写 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

返回或设置线起点的箭头宽度。可读写 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**Returns:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

返回或设置线起点的箭头宽度。可读写 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

返回或设置线终点的箭头宽度。可读写 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**Returns:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

返回或设置线终点的箭头宽度。可读写 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

返回或设置线起点的箭头长度。可读写 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**Returns:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

返回或设置线起点的箭头长度。可读写 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

返回或设置线终点的箭头长度。可读写 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**Returns:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

返回或设置线终点的箭头长度。可读写 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

确定两个 LineFormat 实例是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | 要与当前 LineFormat 比较的 LineFormat。 |

**Returns:**
boolean - **true** if the specified LineFormat is equal to the current LineFormat; otherwise, **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

获取应用继承后的有效线格式化数据。

--------------------

> ```
> 此示例演示获取形状的有效线格式属性。
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - 一个 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).