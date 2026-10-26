---
title: ILineFormatEffectiveData
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đối tượng bất biến chứa các thuộc tính định dạng dòng hiệu quả.
type: docs
url: /vi/com.aspose.slides/ilineformateffectivedata/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Đối tượng bất biến chứa các thuộc tính định dạng dòng hiệu quả.

--------------------

Giao diện này được sử dụng cùng với giao diện [ILineFormat](../../com.aspose.slides/ilineformat) để trả về các giá trị định dạng hiệu quả có áp dụng kế thừa.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Trả về định dạng đổ màu của một dòng. |
| [getSketchFormat()](#getSketchFormat--) | Trả về định dạng phác họa của một dòng. |
| [getWidth()](#getWidth--) | Trả về độ rộng của một dòng. |
| [getDashStyle()](#getDashStyle--) | Trả về kiểu gạch đứt của một dòng. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Trả về mẫu gạch đứt tùy chỉnh. |
| [getCapStyle()](#getCapStyle--) | Trả về kiểu đầu mũi của một dòng. |
| [getStyle()](#getStyle--) | Trả về kiểu đường của một dòng. |
| [getAlignment()](#getAlignment--) | Trả về căn chỉnh dòng. |
| [getJoinStyle()](#getJoinStyle--) | Trả về kiểu nối các đường. |
| [getMiterLimit()](#getMiterLimit--) | Trả về giới hạn miter của một dòng. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Trả về kiểu mũi tên ở đầu một dòng. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Trả về kiểu mũi tên ở cuối một dòng. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Trả về độ rộng mũi tên ở đầu một dòng. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Trả về độ rộng mũi tên ở cuối một dòng. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Trả về chiều dài mũi tên ở đầu một dòng. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Trả về chiều dài mũi tên ở cuối một dòng. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Xác định xem hai đối tượng ILineFormatEffectiveData có bằng nhau không. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Trả về định dạng đổ màu của một dòng. Chỉ đọc [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Trả về:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Trả về định dạng phác họa của một dòng. Chỉ đọc [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Trả về:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Trả về độ rộng của một dòng. Chỉ đọc double.

**Trả về:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Trả về kiểu gạch đứt của một dòng. Chỉ đọc [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Trả về:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Trả về mẫu gạch đứt tùy chỉnh. Chỉ đọc float[].

**Trả về:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Trả về kiểu đầu mũi của một dòng. Chỉ đọc [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Trả về:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Trả về kiểu đường của một dòng. Chỉ đọc [LineStyle](../../com.aspose.slides/linestyle).

**Trả về:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Trả về căn chỉnh dòng. Chỉ đọc [LineAlignment](../../com.aspose.slides/linealignment).

**Trả về:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Trả về kiểu nối các đường. Chỉ đọc [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Trả về:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Trả về giới hạn miter của một dòng. Chỉ đọc float.

**Trả về:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Trả về kiểu mũi tên ở đầu một dòng. Chỉ đọc [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Trả về:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Trả về kiểu mũi tên ở cuối một dòng. Chỉ đọc [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Trả về:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Trả về độ rộng mũi tên ở đầu một dòng. Chỉ đọc [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Trả về:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Trả về độ rộng mũi tên ở cuối một dòng. Chỉ đọc [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Trả về:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Trả về chiều dài mũi tên ở đầu một dòng. Chỉ đọc [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Trả về:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Trả về chiều dài mũi tên ở cuối một dòng. Chỉ đọc [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Trả về:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Xác định xem hai đối tượng ILineFormatEffectiveData có bằng nhau không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | ILineFormatEffectiveData để so sánh với ILineFormatEffectiveData hiện tại. |

**Trả về:**
boolean - **true** nếu ILineFormatEffectiveData được chỉ định bằng với ILineFormatEffectiveData hiện tại; ngược lại, **false**.