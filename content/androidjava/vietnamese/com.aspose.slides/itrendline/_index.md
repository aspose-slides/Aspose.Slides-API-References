---
title: ITrendline
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Lớp đại diện cho đường xu hướng của chuỗi biểu đồ
type: docs
url: /vi/com.aspose.slides/itrendline/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Lớp đại diện cho đường xu hướng của chuỗi biểu đồ
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Lấy hoặc đặt tên của đường xu hướng. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Lấy hoặc đặt tên của đường xu hướng. |
| [getTrendlineType()](#getTrendlineType--) | Lấy hoặc đặt kiểu của đường xu hướng. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Lấy hoặc đặt kiểu của đường xu hướng. |
| [getFormat()](#getFormat--) | Biểu diễn định dạng của đường xu hướng. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Biểu diễn định dạng của đường xu hướng. |
| [getBackward()](#getBackward--) | Xác định số danh mục (hoặc đơn vị trên biểu đồ phân tán) mà đường xu hướng mở rộng trước dữ liệu của chuỗi đang được xu hướng hoá. |
| [setBackward(double value)](#setBackward-double-) | Xác định số danh mục (hoặc đơn vị trên biểu đồ phân tán) mà đường xu hướng mở rộng trước dữ liệu của chuỗi đang được xu hướng hoá. |
| [getForward()](#getForward--) | Xác định số danh mục (hoặc đơn vị trên biểu đồ phân tán) mà đường xu hướng mở rộng sau dữ liệu của chuỗi đang được xu hướng hoá. |
| [setForward(double value)](#setForward-double-) | Xác định số danh mục (hoặc đơn vị trên biểu đồ phân tán) mà đường xu hướng mở rộng sau dữ liệu của chuỗi đang được xu hướng hoá. |
| [getIntercept()](#getIntercept--) | Xác định giá trị mà đường xu hướng sẽ cắt trục y. |
| [setIntercept(double value)](#setIntercept-double-) | Xác định giá trị mà đường xu hướng sẽ cắt trục y. |
| [getDisplayEquation()](#getDisplayEquation--) | Xác định rằng phương trình của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Xác định rằng phương trình của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với Rsquaredvalue). |
| [getOrder()](#getOrder--) | Xác định thứ tự của đường xu hướng đa thức. |
| [setOrder(byte value)](#setOrder-byte-) | Xác định thứ tự của đường xu hướng đa thức. |
| [getPeriod()](#getPeriod--) | Xác định chu kỳ của đường xu hướng cho đường xu hướng trung bình động. |
| [setPeriod(byte value)](#setPeriod-byte-) | Xác định chu kỳ của đường xu hướng cho đường xu hướng trung bình động. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Xác định rằng giá trị R-squared của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với phương trình). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Xác định rằng giá trị R-squared của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với phương trình). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Biểu diễn mục chú giải liên quan tới đường xu hướng này Chỉ-đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Lấy hoặc đặt tên của đường xu hướng. Đọc/ghi String.

**Trả về:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Lấy hoặc đặt tên của đường xu hướng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Lấy hoặc đặt kiểu của đường xu hướng. Đọc/ghi [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Trả về:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Lấy hoặc đặt kiểu của đường xu hướng. Đọc/ghi [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Biểu diễn định dạng của đường xu hướng. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Biểu diễn định dạng của đường xu hướng. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Xác định số danh mục (hoặc đơn vị trên biểu đồ phân tán) mà đường xu hướng mở rộng trước dữ liệu của chuỗi đang được xu hướng hoá. Trên biểu đồ phân tán và không phải phân tán, giá trị phải là bất kỳ giá trị không âm nào. Đọc/ghi double.

**Trả về:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Xác định số danh mục (hoặc đơn vị trên biểu đồ phân tán) mà đường xu hướng mở rộng trước dữ liệu của chuỗi đang được xu hướng hoá. Trên biểu đồ phân tán và không phải phân tán, giá trị phải là bất kỳ giá trị không âm nào. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

Xác định số danh mục (hoặc đơn vị trên biểu đồ phân tán) mà đường xu hướng mở rộng sau dữ liệu của chuỗi đang được xu hướng hoá. Trên biểu đồ phân tán và không phải phân tán, giá trị phải là bất kỳ giá trị không âm nào. Đọc/ghi double.

**Trả về:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Xác định số danh mục (hoặc đơn vị trên biểu đồ phân tán) mà đường xu hướng mở rộng sau dữ liệu của chuỗi đang được xu hướng hoá. Trên biểu đồ phân tán và không phải phân tán, giá trị phải là bất kỳ giá trị không âm nào. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Xác định giá trị mà đường xu hướng sẽ cắt trục y. Thuộc tính này chỉ được hỗ trợ khi kiểu đường xu hướng là exp, linear hoặc poly. Đọc/ghi double.

**Trả về:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Xác định giá trị mà đường xu hướng sẽ cắt trục y. Thuộc tính này chỉ được hỗ trợ khi kiểu đường xu hướng là exp, linear hoặc poly. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Xác định rằng phương trình của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với Rsquaredvalue). Đọc/ghi boolean.

**Trả về:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Xác định rằng phương trình của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với Rsquaredvalue). Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Xác định thứ tự của đường xu hướng đa thức. Giá trị này bị bỏ qua đối với các kiểu đường xu hướng khác. Giá trị phải nằm trong khoảng từ 2 tới 6. Đọc/ghi byte.

**Trả về:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Xác định thứ tự của đường xu hướng đa thức. Giá trị này bị bỏ qua đối với các kiểu đường xu hướng khác. Giá trị phải nằm trong khoảng từ 2 tới 6. Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Xác định chu kỳ của đường xu hướng cho đường xu hướng trung bình động. Giá trị này bị bỏ qua đối với các biến thể đường xu hướng khác. Giá trị phải nằm trong khoảng từ 2 tới 255. Đọc/ghi byte.

**Trả về:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Xác định chu kỳ của đường xu hướng cho đường xu hướng trung bình động. Giá trị này bị bỏ qua đối với các biến thể đường xu hướng khác. Giá trị phải nằm trong khoảng từ 2 tới 255. Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Xác định rằng giá trị R-squared của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với phương trình). Đọc/ghi boolean.

**Trả về:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Xác định rằng giá trị R-squared của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với phương trình). Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Biểu diễn mục chú giải liên quan tới đường xu hướng này Chỉ-đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Trả về:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)