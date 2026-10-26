---
title: ILineFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho định dạng của một đường.
type: docs
url: /vi/com.aspose.slides/ilineformat/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Đại diện cho định dạng của một đường.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Trả về true nếu định dạng đường chưa được xác định (như mới tạo, mặc định). |
| [getFillFormat()](#getFillFormat--) | Trả về định dạng tô màu của một đường. |
| [getSketchFormat()](#getSketchFormat--) | Trả về định dạng phác thảo của một đường. |
| [getWidth()](#getWidth--) | Trả về hoặc đặt độ rộng của một đường. |
| [setWidth(double value)](#setWidth-double-) | Trả về hoặc đặt độ rộng của một đường. |
| [getDashStyle()](#getDashStyle--) | Trả về hoặc đặt kiểu gạch đứt của đường. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Trả về hoặc đặt kiểu gạch đứt của đường. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Trả về hoặc đặt mẫu gạch tùy chỉnh. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Trả về hoặc đặt mẫu gạch tùy chỉnh. |
| [getCapStyle()](#getCapStyle--) | Trả về hoặc đặt kiểu đầu mút của đường. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Trả về hoặc đặt kiểu đầu mút của đường. |
| [getStyle()](#getStyle--) | Trả về hoặc đặt kiểu đường. |
| [setStyle(byte value)](#setStyle-byte-) | Trả về hoặc đặt kiểu đường. |
| [getAlignment()](#getAlignment--) | Trả về hoặc đặt căn chỉnh đường. |
| [setAlignment(byte value)](#setAlignment-byte-) | Trả về hoặc đặt căn chỉnh đường. |
| [getJoinStyle()](#getJoinStyle--) | Trả về hoặc đặt kiểu nối các đường. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Trả về hoặc đặt kiểu nối các đường. |
| [getMiterLimit()](#getMiterLimit--) | Trả về hoặc đặt giới hạn góc nhọn của một đường. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Trả về hoặc đặt giới hạn góc nhọn của một đường. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Trả về hoặc đặt kiểu mũi tên ở đầu đường. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Trả về hoặc đặt kiểu mũi tên ở đầu đường. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Trả về hoặc đặt kiểu mũi tên ở cuối đường. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Trả về hoặc đặt kiểu mũi tên ở cuối đường. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Trả về hoặc đặt độ rộng mũi tên ở đầu đường. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Trả về hoặc đặt độ rộng mũi tên ở đầu đường. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Trả về hoặc đặt độ rộng mũi tên ở cuối đường. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Trả về hoặc đặt độ rộng mũi tên ở cuối đường. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Trả về hoặc đặt độ dài mũi tên ở đầu đường. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Trả về hoặc đặt độ dài mũi tên ở đầu đường. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Trả về hoặc đặt độ dài mũi tên ở cuối đường. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Trả về hoặc đặt độ dài mũi tên ở cuối đường. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Xác định liệu hai đối tượng LineFormat có bằng nhau hay không. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng đường hiệu quả với tính kế thừa được áp dụng. |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```


Trả về true nếu định dạng đường chưa được xác định (như mới tạo, mặc định). Chỉ đọc boolean.

**Trả về:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```


Trả về định dạng tô màu của một đường. Chỉ đọc [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Trả về:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```


Trả về định dạng phác thảo của một đường. Chỉ đọc [ISketchFormat](../../com.aspose.slides/isketchformat).

**Trả về:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Trả về hoặc đặt độ rộng của một đường. Đọc/ghi double.

**Trả về:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Trả về hoặc đặt độ rộng của một đường. Đọc/ ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Trả về hoặc đặt kiểu gạch đứt của đường. Đọc/ ghi [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Trả về:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```


Trả về hoặc đặt kiểu gạch đứt của đường. Đọc/ ghi [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Trả về hoặc đặt mẫu gạch tùy chỉnh. Đọc/ ghi float[].

**Trả về:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```


Trả về hoặc đặt mẫu gạch tùy chỉnh. Đọc/ ghi float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Trả về hoặc đặt kiểu đầu mút của đường. Đọc/ ghi [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Trả về:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```


Trả về hoặc đặt kiểu đầu mút của đường. Đọc/ ghi [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Trả về hoặc đặt kiểu đường. Đọc/ ghi [LineStyle](../../com.aspose.slides/linestyle).

**Trả về:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```


Trả về hoặc đặt kiểu đường. Đọc/ ghi [LineStyle](../../com.aspose.slides/linestyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Trả về hoặc đặt căn chỉnh đường. Đọc/ ghi [LineAlignment](../../com.aspose.slides/linealignment).

**Trả về:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```


Trả về hoặc đặt căn chỉnh đường. Đọc/ ghi [LineAlignment](../../com.aspose.slides/linealignment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Trả về hoặc đặt kiểu nối các đường. Đọc/ ghi [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Trả về:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```


Trả về hoặc đặt kiểu nối các đường. Đọc/ ghi [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Trả về hoặc đặt giới hạn góc nhọn của một đường. Đọc/ ghi float.

**Trả về:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```


Trả về hoặc đặt giới hạn góc nhọn của một đường. Đọc/ ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Trả về hoặc đặt kiểu mũi tên ở đầu đường. Đọc/ ghi [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Trả về:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```


Trả về hoặc đặt kiểu mũi tên ở đầu đường. Đọc/ ghi [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Trả về hoặc đặt kiểu mũi tên ở cuối đường. Đọc/ ghi [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Trả về:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```


Trả về hoặc đặt kiểu mũi tên ở cuối đường. Đọc/ ghi [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Trả về hoặc đặt độ rộng mũi tên ở đầu đường. Đọc/ ghi [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Trả về:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```


Trả về hoặc đặt độ rộng mũi tên ở đầu đường. Đọc/ ghi [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Trả về hoặc đặt độ rộng mũi tên ở cuối đường. Đọc/ ghi [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Trả về:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```


Trả về hoặc đặt độ rộng mũi tên ở cuối đường. Đọc/ ghi [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Trả về hoặc đặt độ dài mũi tên ở đầu đường. Đọc/ ghi [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Trả về:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```


Trả về hoặc đặt độ dài mũi tên ở đầu đường. Đọc/ ghi [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Trả về hoặc đặt độ dài mũi tên ở cuối đường. Đọc/ ghi [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Trả về:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```


Trả về hoặc đặt độ dài mũi tên ở cuối đường. Đọc/ ghi [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```


Xác định liệu hai đối tượng LineFormat có bằng nhau hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Đối tượng LineFormat để so sánh với đối tượng LineFormat hiện tại. |

**Trả về:**
boolean - **true** nếu LineFormat được chỉ định bằng với LineFormat hiện tại; ngược lại, **false**.
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```


Lấy dữ liệu định dạng đường hiệu quả với tính kế thừa được áp dụng.

**Trả về:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Một [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).