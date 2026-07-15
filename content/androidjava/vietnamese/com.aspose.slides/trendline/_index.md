---
title: Trendline
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Lớp đại diện cho đường xu hướng của chuỗi biểu đồ
type: docs
url: /vi/com.aspose.slides/trendline/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Lớp đại diện cho đường xu hướng của chuỗi biểu đồ
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Lấy hoặc đặt tên của đường xu hướng. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Lấy hoặc đặt tên của đường xu hướng. |
| [getTrendlineType()](#getTrendlineType--) | Lấy hoặc đặt loại của đường xu hướng. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Lấy hoặc đặt loại của đường xu hướng. |
| [getFormat()](#getFormat--) | Đại diện cho định dạng của đường xu hướng. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Đại diện cho định dạng của đường xu hướng. |
| [getBackward()](#getBackward--) | Xác định số danh mục (hoặc đơn vị trên biểu đồ scatter) mà đường xu hướng mở rộng trước dữ liệu của chuỗi đang được xu hướng. |
| [setBackward(double value)](#setBackward-double-) | Xác định số danh mục (hoặc đơn vị trên biểu đồ scatter) mà đường xu hướng mở rộng trước dữ liệu của chuỗi đang được xu hướng. |
| [getForward()](#getForward--) | Xác định số danh mục (hoặc đơn vị trên biểu đồ scatter) mà đường xu hướng mở rộng sau dữ liệu của chuỗi đang được xu hướng. |
| [setForward(double value)](#setForward-double-) | Xác định số danh mục (hoặc đơn vị trên biểu đồ scatter) mà đường xu hướng mở rộng sau dữ liệu của chuỗi đang được xu hướng. |
| [getIntercept()](#getIntercept--) | Xác định giá trị mà đường xu hướng sẽ cắt trục y. |
| [setIntercept(double value)](#setIntercept-double-) | Xác định giá trị mà đường xu hướng sẽ cắt trục y. |
| [getDisplayEquation()](#getDisplayEquation--) | Xác định rằng phương trình của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với giá trị Rsquared). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Xác định rằng phương trình của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với giá trị Rsquared). |
| [getOrder()](#getOrder--) | Xác định thứ tự của đường xu hướng đa thức. |
| [setOrder(byte value)](#setOrder-byte-) | Xác định thứ tự của đường xu hướng đa thức. |
| [getPeriod()](#getPeriod--) | Xác định chu kỳ của đường xu hướng cho đường xu hướng trung bình động. |
| [setPeriod(byte value)](#setPeriod-byte-) | Xác định chu kỳ của đường xu hướng cho đường xu hướng trung bình động. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Xác định rằng giá trị R-squared của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với phương trình). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Xác định rằng giá trị R-squared của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với phương trình). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Đại diện cho mục nhập chú giải liên quan đến đường xu hướng này Chỉ đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Khởi tạo TextFrameForOverriding bằng văn bản trong tham số "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Có thể chứa văn bản được định dạng phong phú. |
| [getTextFormat()](#getTextFormat--) | Trả về định dạng văn bản. |
| [getChart()](#getChart--) | Trả về biểu đồ cha. |
| [getSlide()](#getSlide--) | Trả về slide cha của FillFormat. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của FillFormat. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Lấy hoặc đặt tên của đường xu hướng. Đọc/ghi String.

**Trả về:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Lấy hoặc đặt tên của đường xu hướng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Lấy hoặc đặt loại của đường xu hướng. Đọc/ghi [TrendlineType](../../com.aspose.slides/trendlinetype).

**Trả về:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Lấy hoặc đặt loại của đường xu hướng. Đọc/ghi [TrendlineType](../../com.aspose.slides/trendlinetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Đại diện cho định dạng của đường xu hướng. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Đại diện cho định dạng của đường xu hướng. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

Xác định số danh mục (hoặc đơn vị trên biểu đồ scatter) mà đường xu hướng mở rộng trước dữ liệu của chuỗi đang được xu hướng. Trên biểu đồ scatter và không scatter, giá trị phải là bất kỳ giá trị không âm nào. Đọc/ghi double.

**Trả về:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Xác định số danh mục (hoặc đơn vị trên biểu đồ scatter) mà đường xu hướng mở rộng trước dữ liệu của chuỗi đang được xu hướng. Trên biểu đồ scatter và không scatter, giá trị phải là bất kỳ giá trị không âm nào. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

Xác định số danh mục (hoặc đơn vị trên biểu đồ scatter) mà đường xu hướng mở rộng sau dữ liệu của chuỗi đang được xu hướng. Trên biểu đồ scatter và không scatter, giá trị phải là bất kỳ giá trị không âm nào. Đọc/ghi double.

**Trả về:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Xác định số danh mục (hoặc đơn vị trên biểu đồ scatter) mà đường xu hướng mở rộng sau dữ liệu của chuỗi đang được xu hướng. Trên biểu đồ scatter và không scatter, giá trị phải là bất kỳ giá trị không âm nào. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Xác định giá trị mà đường xu hướng sẽ cắt trục y. Thuộc tính này chỉ được hỗ trợ khi loại đường xu hướng là exp, linear hoặc poly. Đọc/ghi double.

**Trả về:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Xác định giá trị mà đường xu hướng sẽ cắt trục y. Thuộc tính này chỉ được hỗ trợ khi loại đường xu hướng là exp, linear hoặc poly. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Xác định rằng phương trình của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với giá trị Rsquared). Đọc/ghi boolean.

**Trả về:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Xác định rằng phương trình của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với giá trị Rsquared). Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Xác định thứ tự của đường xu hướng đa thức. Nó bị bỏ qua cho các loại đường xu hướng khác. Giá trị phải nằm trong khoảng từ 2 đến 6. Đọc/ghi byte.

**Trả về:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Xác định thứ tự của đường xu hướng đa thức. Nó bị bỏ qua cho các loại đường xu hướng khác. Giá trị phải nằm trong khoảng từ 2 đến 6. Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Xác định chu kỳ của đường xu hướng cho đường xu hướng trung bình động. Nó bị bỏ qua cho các biến thể đường xu hướng khác. Giá trị phải nằm trong khoảng từ 2 đến 255. Đọc/ghi byte.

**Trả về:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Xác định chu kỳ của đường xu hướng cho đường xu hướng trung bình động. Nó bị bỏ qua cho các biến thể đường xu hướng khác. Giá trị phải nằm trong khoảng từ 2 đến 255. Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Xác định rằng giá trị R-squared của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với phương trình). Đọc/ghi boolean.

**Trả về:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Xác định rằng giá trị R-squared của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với phương trình). Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Đại diện cho mục nhập chú giải liên quan đến đường xu hướng này Chỉ đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Trả về:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Khởi tạo TextFrameForOverriding bằng văn bản trong tham số "text". Nếu TextFrameForOverriding đã được khởi tạo thì chỉ thay đổi văn bản của nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cho TextFrameForOverriding mới. |

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Có thể chứa văn bản được định dạng phong phú. Nếu thuộc tính này không null thì giá trị văn bản đã định dạng này sẽ ghi đè lên văn bản tự động tạo của nhãn dữ liệu. Văn bản tự động tạo của nhãn dữ liệu có nghĩa là văn bản do các thuộc tính ShowSeriesName, ShowValue, ... quản lý và được định dạng bằng thuộc tính TextFormatManager.TextFormat. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Trả về định dạng văn bản. Chỉ đọc [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Trả về:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Trả về biểu đồ cha. Chỉ đọc [IChart](../../com.aspose.slides/ichart).

**Trả về:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của FillFormat. Chỉ đọc [BaseSlide](../../com.aspose.slides/baseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của FillFormat. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)