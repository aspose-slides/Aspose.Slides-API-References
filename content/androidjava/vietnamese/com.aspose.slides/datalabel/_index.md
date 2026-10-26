---
title: DataLabel
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn các nhãn chuỗi.
type: docs
url: /vi/com.aspose.slides/datalabel/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Biểu diễn các nhãn chuỗi.
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Tạo một thể hiện mới của lớp DataLabel. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Trả về biểu đồ cha. |
| [isVisible()](#isVisible--) | False có nghĩa là nhãn dữ liệu không hiển thị (vì vậy tất cả các cờ Show*-flags (ShowValue, ...) đều sai). |
| [hide()](#hide--) | Ẩn nhãn dữ liệu bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) ở trạng thái false. |
| [getActualLabelText()](#getActualLabelText--) | Trả về văn bản nhãn thực tế dựa trên cài đặt DataLabelFormat hoặc giá trị TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Khởi tạo TextFrameForOverriding bằng văn bản trong tham số "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Có thể chứa văn bản định dạng phong phú. |
| [getTextFormat()](#getTextFormat--) | Trả về định dạng văn bản. |
| [getX()](#getX--) | Trả về hoặc đặt tọa độ x của tiêu đề như một phần của chiều rộng biểu đồ. |
| [setX(float value)](#setX-float-) | Trả về hoặc đặt tọa độ x của tiêu đề như một phần của chiều rộng biểu đồ. |
| [getY()](#getY--) | Trả về hoặc đặt tọa độ y của tiêu đề như một phần của chiều cao biểu đồ. |
| [setY(float value)](#setY-float-) | Trả về hoặc đặt tọa độ y của tiêu đề như một phần của chiều cao biểu đồ. |
| [getWidth()](#getWidth--) | Trả về hoặc đặt chiều rộng của tiêu đề như một phần của chiều rộng biểu đồ. |
| [setWidth(float value)](#setWidth-float-) | Trả về hoặc đặt chiều rộng của tiêu đề như một phần của chiều rộng biểu đồ. |
| [getHeight()](#getHeight--) | Trả về hoặc đặt chiều cao của tiêu đề như một phần của chiều cao biểu đồ. |
| [setHeight(float value)](#setHeight-float-) | Trả về hoặc đặt chiều cao của tiêu đề như một phần của chiều cao biểu đồ. |
| [getRight()](#getRight--) | Phải. |
| [getBottom()](#getBottom--) | Dưới. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Trả về định dạng nhãn dữ liệu. |
| [getValueFromCell()](#getValueFromCell--) | Lấy hoặc đặt ô dữ liệu workbook. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Lấy hoặc đặt ô dữ liệu workbook. |
| [getActualX()](#getActualX--) | Chỉ định vị trí x thực tế (trái) của phần tử biểu đồ so với góc trái trên của biểu đồ. |
| [getActualY()](#getActualY--) | Chỉ định vị trí trên thực tế của phần tử biểu đồ so với góc trái trên của biểu đồ. |
| [getActualWidth()](#getActualWidth--) | Chỉ định chiều rộng thực tế của phần tử biểu đồ. |
| [getActualHeight()](#getActualHeight--) | Chỉ định chiều cao thực tế của phần tử biểu đồ. |
| [getSlide()](#getSlide--) | Trả về slide cha của FillFormat. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Tạo một thể hiện mới của lớp DataLabel.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint cha. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Trả về biểu đồ cha. Chỉ đọc [IChart](../../com.aspose.slides/ichart).

**Trả về:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False có nghĩa là nhãn dữ liệu không hiển thị (vì vậy tất cả các cờ Show*-flags (ShowValue, ...) đều sai). Chỉ đọc boolean.

--------------------

Nếu nhãn dữ liệu hiển thị bạn có thể ẩn nó bằng phương thức Hide(). Nhưng nếu nhãn dữ liệu không hiển thị (IsVisible là false) bạn có thể làm cho nhãn dữ liệu hiển thị bằng cách đặt các cờ Show*-flags (ShowValue, ...) ở trạng thái true.

**Trả về:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Ẩn nhãn dữ liệu bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) ở trạng thái false. IsVisible sẽ trở thành false sau này.

--------------------

Nếu nhãn dữ liệu không hiển thị (IsVisible là false) bạn có thể làm cho nhãn dữ liệu hiển thị bằng cách đặt các cờ Show*-flags (ShowValue, ...) ở trạng thái true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Trả về văn bản nhãn thực tế dựa trên cài đặt DataLabelFormat hoặc giá trị TextFrameForOverriding.Text.

**Trả về:**
java.lang.String - The java.lang.String object.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Khởi tạo TextFrameForOverriding bằng văn bản trong tham số "text". Nếu TextFrameForOverriding đã được khởi tạo rồi thì chỉ thay đổi văn bản của nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cho một TextFrameForOverriding mới. |

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Có thể chứa văn bản định dạng phong phú. Nếu thuộc tính này không null thì giá trị văn bản định dạng này sẽ ghi đè lên văn bản tự động tạo của nhãn dữ liệu. Văn bản tự động tạo của nhãn dữ liệu là văn bản được quản lý bởi các thuộc tính ShowSeriesName, ShowValue, … và được định dạng bằng thuộc tính TextFormatManager.TextFormat. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Trả về định dạng văn bản. Chỉ đọc [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Trả về:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Trả về hoặc đặt tọa độ x của tiêu đề như một phần của chiều rộng biểu đồ. Đọc/ghi float.

**Trả về:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Trả về hoặc đặt tọa độ x của tiêu đề như một phần của chiều rộng biểu đồ. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Trả về hoặc đặt tọa độ y của tiêu đề như một phần của chiều cao biểu đồ. Đọc/ghi float.

**Trả về:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Trả về hoặc đặt tọa độ y của tiêu đề như một phần của chiều cao biểu đồ. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Trả về hoặc đặt chiều rộng của tiêu đề như một phần của chiều rộng biểu đồ. Đọc/ghi float.

**Trả về:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Trả về hoặc đặt chiều rộng của tiêu đề như một phần của chiều rộng biểu đồ. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Trả về hoặc đặt chiều cao của tiêu đề như một phần của chiều cao biểu đồ. Đọc/ghi float.

**Trả về:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Trả về hoặc đặt chiều cao của tiêu đề như một phần của chiều cao biểu đồ. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Phải. Chỉ đọc float.

**Trả về:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Dưới. Chỉ đọc float.

**Trả về:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Trả về định dạng nhãn dữ liệu. Chỉ đọc [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Trả về:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Lấy hoặc đặt ô dữ liệu workbook. Áp dụng nếu thuộc tính IDataLabelFormat.ShowLabelValueFromCell bằng true.

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Lấy hoặc đặt ô dữ liệu workbook. Áp dụng nếu thuộc tính IDataLabelFormat.ShowLabelValueFromCell bằng true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Chỉ định vị trí x thực tế (trái) của phần tử biểu đồ so với góc trái trên của biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Chỉ đọc float.

**Trả về:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Chỉ định vị trí trên thực tế của phần tử biểu đồ so với góc trái trên của biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Chỉ đọc float.

**Trả về:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Chỉ định chiều rộng thực tế của phần tử biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Chỉ đọc float.

**Trả về:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Chỉ định chiều cao thực tế của phần tử biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Chỉ đọc float.

**Trả về:**
float
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