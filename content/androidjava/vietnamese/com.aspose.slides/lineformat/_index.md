---
title: LineFormat
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn định dạng của một đường.
type: docs
url: /vi/com.aspose.slides/lineformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Biểu diễn định dạng của một đường.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Trả về true nếu định dạng đường chưa được xác định (khi mới tạo, mặc định). |
| [getFillFormat()](#getFillFormat--) | Trả về định dạng tô màu của một đường. |
| [getSketchFormat()](#getSketchFormat--) | Trả về định dạng phác thảo của một đường. |
| [getWidth()](#getWidth--) | Trả về hoặc đặt độ rộng của một đường. |
| [setWidth(double value)](#setWidth-double-) | Trả về hoặc đặt độ rộng của một đường. |
| [getDashStyle()](#getDashStyle--) | Trả về hoặc đặt kiểu gạch đứt của một đường. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Trả về hoặc đặt kiểu gạch đứt của một đường. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Trả về hoặc đặt mẫu gạch chấm tùy chỉnh. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Trả về hoặc đặt mẫu gạch chấm tùy chỉnh. |
| [getCapStyle()](#getCapStyle--) | Trả về hoặc đặt kiểu đầu mút của một đường. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Trả về hoặc đặt kiểu đầu mút của một đường. |
| [getStyle()](#getStyle--) | Trả về hoặc đặt kiểu đường. |
| [setStyle(byte value)](#setStyle-byte-) | Trả về hoặc đặt kiểu đường. |
| [getAlignment()](#getAlignment--) | Trả về hoặc đặt căn chỉnh của một đường. |
| [setAlignment(byte value)](#setAlignment-byte-) | Trả về hoặc đặt căn chỉnh của một đường. |
| [getJoinStyle()](#getJoinStyle--) | Trả về hoặc đặt kiểu nối của các đường. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Trả về hoặc đặt kiểu nối của các đường. |
| [getMiterLimit()](#getMiterLimit--) | Trả về hoặc đặt giới hạn miter của một đường. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Trả về hoặc đặt giới hạn miter của một đường. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Trả về hoặc đặt kiểu mũi tên ở đầu một đường. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Trả về hoặc đặt kiểu mũi tên ở đầu một đường. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Trả về hoặc đặt kiểu mũi tên ở cuối một đường. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Trả về hoặc đặt kiểu mũi tên ở cuối một đường. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Trả về hoặc đặt độ rộng mũi tên ở đầu một đường. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Trả về hoặc đặt độ rộng mũi tên ở đầu một đường. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Trả về hoặc đặt độ rộng mũi tên ở cuối một đường. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Trả về hoặc đặt độ rộng mũi tên ở cuối một đường. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Trả về hoặc đặt độ dài mũi tên ở đầu một đường. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Trả về hoặc đặt độ dài mũi tên ở đầu một đường. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Trả về hoặc đặt độ dài mũi tên ở cuối một đường. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Trả về hoặc đặt độ dài mũi tên ở cuối một đường. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Xác định liệu hai đối tượng LineFormat có bằng nhau hay không. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng đường hiệu quả với tính kế thừa đã áp dụng. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

So sánh với đối tượng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Trả về:**
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

Trả về true nếu định dạng đường chưa được xác định (khi mới tạo, mặc định). Chỉ đọc boolean.

**Trả về:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Trả về định dạng tô màu của một đường. Chỉ đọc [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Trả về:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Trả về định dạng phác thảo của một đường. Chỉ đọc [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Trả về:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Trả về hoặc đặt độ rộng của một đường. Đọc/ghi double.

**Trả về:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Trả về hoặc đặt độ rộng của một đường. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Trả về hoặc đặt kiểu gạch đứt của một đường. Đọc/ghi [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Trả về:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Trả về hoặc đặt kiểu gạch đứt của một đường. Đọc/ghi [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Trả về hoặc đặt mẫu gạch chấm tùy chỉnh. Đọc/ghi float[].

**Trả về:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Trả về hoặc đặt mẫu gạch chấm tùy chỉnh. Đọc/ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Trả về hoặc đặt kiểu đầu mút của một đường. Đọc/ghi [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Trả về:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Trả về hoặc đặt kiểu đầu mút của một đường. Đọc/ghi [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Trả về hoặc đặt kiểu đường. Đọc/ghi [LineStyle](../../com.aspose.slides/linestyle).

**Trả về:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Trả về hoặc đặt kiểu đường. Đọc/ghi [LineStyle](../../com.aspose.slides/linestyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Trả về hoặc đặt căn chỉnh của một đường. Đọc/ghi [LineAlignment](../../com.aspose.slides/linealignment).

**Trả về:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Trả về hoặc đặt căn chỉnh của một đường. Đọc/ghi [LineAlignment](../../com.aspose.slides/linealignment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Trả về hoặc đặt kiểu nối của các đường. Đọc/ghi [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Trả về:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Trả về hoặc đặt kiểu nối của các đường. Đọc/ghi [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Trả về hoặc đặt giới hạn miter của một đường. Đọc/ghi float.

**Trả về:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Trả về hoặc đặt giới hạn miter của một đường. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Trả về hoặc đặt kiểu mũi tên ở đầu một đường. Đọc/ghi [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Trả về:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Trả về hoặc đặt kiểu mũi tên ở đầu một đường. Đọc/ghi [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Trả về hoặc đặt kiểu mũi tên ở cuối một đường. Đọc/ghi [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Trả về:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Trả về hoặc đặt kiểu mũi tên ở cuối một đường. Đọc/ghi [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Trả về hoặc đặt độ rộng mũi tên ở đầu một đường. Đọc/ghi [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Trả về:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Trả về hoặc đặt độ rộng mũi tên ở đầu một đường. Đọc/ghi [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Trả về hoặc đặt độ rộng mũi tên ở cuối một đường. Đọc/ghi [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Trả về:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Trả về hoặc đặt độ rộng mũi tên ở cuối một đường. Đọc/ghi [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Trả về hoặc đặt độ dài mũi tên ở đầu một đường. Đọc/ghi [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Trả về:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Trả về hoặc đặt độ dài mũi tên ở đầu một đường. Đọc/ghi [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Trả về hoặc đặt độ dài mũi tên ở cuối một đường. Đọc/ghi [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Trả về:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Trả về hoặc đặt độ dài mũi tên ở cuối một đường. Đọc/ghi [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

Xác định liệu hai đối tượng LineFormat có bằng nhau hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat để so sánh với LineFormat hiện tại. |

**Trả về:**
boolean - **true** nếu LineFormat được chỉ định bằng với LineFormat hiện tại; ngược lại, **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Lấy dữ liệu định dạng đường hiệu quả với tính kế thừa đã áp dụng.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
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


**Trả về:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).