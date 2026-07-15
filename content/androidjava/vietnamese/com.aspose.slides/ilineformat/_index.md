---
title: ILineFormat
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Mô tả định dạng của một dòng.
type: docs
url: /vi/com.aspose.slides/ilineformat/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Mô tả định dạng của một dòng.
## Phương thức

| Method | Mô tả |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Trả về true nếu định dạng dòng không được xác định (như mới tạo, mặc định). |
| [getFillFormat()](#getFillFormat--) | Trả về định dạng tô màu của một dòng. |
| [getSketchFormat()](#getSketchFormat--) | Trả về định dạng phác thảo của một dòng. |
| [getWidth()](#getWidth--) | Trả về hoặc đặt chiều rộng của một dòng. |
| [setWidth(double value)](#setWidth-double-) | Trả về hoặc đặt chiều rộng của một dòng. |
| [getDashStyle()](#getDashStyle--) | Trả về hoặc đặt kiểu gạch ngang của dòng. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Trả về hoặc đặt kiểu gạch ngang của dòng. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Trả về hoặc đặt mẫu gạch tùy chỉnh. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Trả về hoặc đặt mẫu gạch tùy chỉnh. |
| [getCapStyle()](#getCapStyle--) | Trả về hoặc đặt kiểu đầu mút của dòng. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Trả về hoặc đặt kiểu đầu mút của dòng. |
| [getStyle()](#getStyle--) | Trả về hoặc đặt kiểu dòng. |
| [setStyle(byte value)](#setStyle-byte-) | Trả về hoặc đặt kiểu dòng. |
| [getAlignment()](#getAlignment--) | Trả về hoặc đặt căn chỉnh dòng. |
| [setAlignment(byte value)](#setAlignment-byte-) | Trả về hoặc đặt căn chỉnh dòng. |
| [getJoinStyle()](#getJoinStyle--) | Trả về hoặc đặt kiểu nối của các dòng. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Trả về hoặc đặt kiểu nối của các dòng. |
| [getMiterLimit()](#getMiterLimit--) | Trả về hoặc đặt giới hạn mối của một dòng. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Trả về hoặc đặt giới hạn mối của một dòng. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Trả về hoặc đặt kiểu mũi tên ở đầu một dòng. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Trả về hoặc đặt kiểu mũi tên ở đầu một dòng. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Trả về hoặc đặt kiểu mũi tên ở cuối một dòng. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Trả về hoặc đặt kiểu mũi tên ở cuối một dòng. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Trả về hoặc đặt độ rộng mũi tên ở đầu một dòng. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Trả về hoặc đặt độ rộng mũi tên ở đầu một dòng. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Trả về hoặc đặt độ rộng mũi tên ở cuối một dòng. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Trả về hoặc đặt độ rộng mũi tên ở cuối một dòng. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Trả về hoặc đặt độ dài mũi tên ở đầu một dòng. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Trả về hoặc đặt độ dài mũi tên ở đầu một dòng. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Trả về hoặc đặt độ dài mũi tên ở cuối một dòng. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Trả về hoặc đặt độ dài mũi tên ở cuối một dòng. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Xác định xem hai đối tượng LineFormat có bằng nhau hay không. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng dòng hiệu quả với kế thừa được áp dụng. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Trả về true nếu định dạng dòng không được xác định (như mới tạo, mặc định). **boolean** chỉ đọc.

**Trả về:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Trả về định dạng tô màu của một dòng. **[ILineFillFormat](../../com.aspose.slides/ilinefillformat)** chỉ đọc.

**Trả về:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Trả về định dạng phác thảo của một dòng. **[ISketchFormat](../../com.aspose.slides/isketchformat)** chỉ đọc.

**Trả về:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Trả về hoặc đặt chiều rộng của một dòng. double đọc/ghi.

**Trả về:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Trả về hoặc đặt chiều rộng của một dòng. double đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Trả về hoặc đặt kiểu gạch ngang của dòng. [LineDashStyle](../../com.aspose.slides/linedashstyle) đọc/ghi.

**Trả về:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Trả về hoặc đặt kiểu gạch ngang của dòng. [LineDashStyle](../../com.aspose.slides/linedashstyle) đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Trả về hoặc đặt mẫu gạch tùy chỉnh. float[] đọc/ghi.

**Trả về:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Trả về hoặc đặt mẫu gạch tùy chỉnh. float[] đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Trả về hoặc đặt kiểu đầu mút của dòng. [LineCapStyle](../../com.aspose.slides/linecapstyle) đọc/ghi.

**Trả về:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Trả về hoặc đặt kiểu đầu mút của dòng. [LineCapStyle](../../com.aspose.slides/linecapstyle) đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Trả về hoặc đặt kiểu dòng. [LineStyle](../../com.aspose.slides/linestyle) đọc/ghi.

**Trả về:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Trả về hoặc đặt kiểu dòng. [LineStyle](../../com.aspose.slides/linestyle) đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Trả về hoặc đặt căn chỉnh dòng. [LineAlignment](../../com.aspose.slides/linealignment) đọc/ghi.

**Trả về:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Trả về hoặc đặt căn chỉnh dòng. [LineAlignment](../../com.aspose.slides/linealignment) đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Trả về hoặc đặt kiểu nối của các dòng. [LineJoinStyle](../../com.aspose.slides/linejoinstyle) đọc/ghi.

**Trả về:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Trả về hoặc đặt kiểu nối của các dòng. [LineJoinStyle](../../com.aspose.slides/linejoinstyle) đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Trả về hoặc đặt giới hạn mối của một dòng. float đọc/ghi.

**Trả về:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Trả về hoặc đặt giới hạn mối của một dòng. float đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Trả về hoặc đặt kiểu mũi tên ở đầu một dòng. [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle) đọc/ghi.

**Trả về:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Trả về hoặc đặt kiểu mũi tên ở đầu một dòng. [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle) đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Trả về hoặc đặt kiểu mũi tên ở cuối một dòng. [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle) đọc/ghi.

**Trả về:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Trả về hoặc đặt kiểu mũi tên ở cuối một dòng. [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle) đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Trả về hoặc đặt độ rộng mũi tên ở đầu một dòng. [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth) đọc/ghi.

**Trả về:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Trả về hoặc đặt độ rộng mũi tên ở đầu một dòng. [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth) đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Trả về hoặc đặt độ rộng mũi tên ở cuối một dòng. [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth) đọc/ghi.

**Trả về:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Trả về hoặc đặt độ rộng mũi tên ở cuối một dòng. [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth) đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Trả về hoặc đặt độ dài mũi tên ở đầu một dòng. [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength) đọc/ghi.

**Trả về:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Trả về hoặc đặt độ dài mũi tên ở đầu một dòng. [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength) đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Trả về hoặc đặt độ dài mũi tên ở cuối một dòng. [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength) đọc/ghi.

**Trả về:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Trả về hoặc đặt độ dài mũi tên ở cuối một dòng. [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength) đọc/ghi.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Xác định xem hai đối tượng LineFormat có bằng nhau hay không.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Đối tượng LineFormat để so sánh với đối tượng LineFormat hiện tại. |

**Trả về:**
boolean - **true** nếu LineFormat được chỉ định bằng với LineFormat hiện tại; ngược lại, **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Lấy dữ liệu định dạng dòng hiệu quả với kế thừa được áp dụng.

**Trả về:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Một [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).