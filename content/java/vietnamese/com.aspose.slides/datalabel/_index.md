---
title: DataLabel
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho các nhãn chuỗi.
type: docs
url: /vi/com.aspose.slides/datalabel/
---
**Kế thừa:**  
java.lang.Object

**Tất cả các giao diện triển khai:**  
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject  
```
public class DataLabel implements IDataLabel, IDOMObject
```

Đại diện cho các nhãn chuỗi.

## Các hàm khởi tạo

| Constructor | Description |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Tạo một thể hiện mới của lớp DataLabel. |

## Phương thức

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Trả về biểu đồ cha. |
| [isVisible()](#isVisible--) | False có nghĩa là nhãn dữ liệu không hiển thị (và vì vậy tất cả các cờ Show*-flags (ShowValue, ...) đều là false). |
| [hide()](#hide--) | Ẩn nhãn dữ liệu bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) về trạng thái false. |
| [getActualLabelText()](#getActualLabelText--) | Trả về văn bản nhãn thực tế dựa trên cài đặt DataLabelFormat hoặc giá trị TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Khởi tạo TextFrameForOverriding với văn bản trong tham số "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Có thể chứa văn bản định dạng phong phú. |
| [getTextFormat()](#getTextFormat--) | Trả về định dạng văn bản. |
| [getX()](#getX--) | Trả về hoặc đặt tọa độ x của tiêu đề dưới dạng tỷ lệ của chiều rộng biểu đồ. |
| [setX(float value)](#setX-float-) | Trả về hoặc đặt tọa độ x của tiêu đề dưới dạng tỷ lệ của chiều rộng biểu đồ. |
| [getY()](#getY--) | Trả về hoặc đặt tọa độ y của tiêu đề dưới dạng tỷ lệ của chiều cao biểu đồ. |
| [setY(float value)](#setY-float-) | Trả về hoặc đặt tọa độ y của tiêu đề dưới dạng tỷ lệ của chiều cao biểu đồ. |
| [getWidth()](#getWidth--) | Trả về hoặc đặt chiều rộng của tiêu đề dưới dạng tỷ lệ của chiều rộng biểu đồ. |
| [setWidth(float value)](#setWidth-float-) | Trả về hoặc đặt chiều rộng của tiêu đề dưới dạng tỷ lệ của chiều rộng biểu đồ. |
| [getHeight()](#getHeight--) | Trả về hoặc đặt chiều cao của tiêu đề dưới dạng tỷ lệ của chiều cao biểu đồ. |
| [setHeight(float value)](#setHeight-float-) | Trả về hoặc đặt chiều cao của tiêu đề dưới dạng tỷ lệ của chiều cao biểu đồ. |
| [getRight()](#getRight--) | Phải. |
| [getBottom()](#getBottom--) | Duoi. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Trả về định dạng nhãn dữ liệu. |
| [getValueFromCell()](#getValueFromCell--) | Lấy hoặc đặt ô dữ liệu trong workbook. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Lấy hoặc đặt ô dữ liệu trong workbook. |
| [getLabelShapeType()](#getLabelShapeType--) | Lấy hoặc đặt kiểu hình dạng của nhãn dữ liệu. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Lấy hoặc đặt kiểu hình dạng của nhãn dữ liệu. |
| [getActualX()](#getActualX--) | Xác định vị trí x thực tế (trai) của phần tử biểu đồ so với goc tren-trai của biểu đồ. |
| [getActualY()](#getActualY--) | Xác định vị trí y thực tế của phần tử biểu đồ so với goc tren-trai của biểu đồ. |
| [getActualWidth()](#getActualWidth--) | Xác định chiều rộng thực tế của phần tử biểu đồ. |
| [getActualHeight()](#getActualHeight--) | Xác định chiều cao thực tế của phần tử biểu đồ. |
| [getSlide()](#getSlide--) | Trả về slide cha của một FillFormat. |
| [getPresentation()](#getPresentation--) | Trả về presentation cha của một FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Tạo một thể hiện mới của lớp DataLabel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Điểm dữ liệu chart cha. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Trả về biểu đồ cha. Chỉ đọc [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False có nghĩa là nhãn dữ liệu không hiển thị (và vì vậy tất cả các cờ Show*-flags (ShowValue, ...) đều là false). Chỉ đọc boolean.

--------------------

Nếu nhãn dữ liệu hiển thị, bạn có thể ẩn nó bằng phương thức Hide(). Nhưng nếu nhãn dữ liệu không hiển thị (IsVisible là false) bạn có thể làm cho nhãn dữ liệu hiển thị bằng cách đặt các cờ Show*-flags (ShowValue, ...) về trạng thái true.

**Returns:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Ẩn nhãn dữ liệu bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) về trạng thái false. IsVisible sẽ là false sau khi thực hiện.

--------------------

Nếu nhãn dữ liệu không hiển thị (IsVisible là false) bạn có thể làm cho nhãn dữ liệu hiển thị bằng cách đặt các cờ Show*-flags (ShowValue, ...) về trạng thái true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Trả về văn bản nhãn thực tế dựa trên cài đặt DataLabelFormat hoặc giá trị TextFrameForOverriding.Text.

**Returns:**
java.lang.String - Đối tượng java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Khởi tạo TextFrameForOverriding với văn bản trong tham số "text". Nếu TextFrameForOverriding đã được khởi tạo thì chỉ thay đổi văn bản của nó.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Văn bản cho TextFrameForOverriding mới. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Có thể chứa văn bản định dạng phong phú. Nếu thuộc tính này không null thì giá trị văn bản định dạng này sẽ ghi đè lên văn bản tự động tạo của nhãn dữ liệu. Văn bản tự động tạo của nhãn dữ liệu là văn bản được quản lý bởi các thuộc tính ShowSeriesName, ShowValue, ... và được định dạng bằng thuộc tính TextFormatManager.TextFormat. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Trả về định dạng văn bản. Chỉ đọc [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Trả về hoặc đặt tọa độ x của tiêu đề dưới dạng tỷ lệ của chiều rộng biểu đồ. Đọc/ghi float.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Trả về hoặc đặt tọa độ x của tiêu đề dưới dạng tỷ lệ của chiều rộng biểu đồ. Đọc/ghi float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Trả về hoặc đặt tọa độ y của tiêu đề dưới dạng tỷ lệ của chiều cao biểu đồ. Đọc/ghi float.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Trả về hoặc đặt tọa độ y của tiêu đề dưới dạng tỷ lệ của chiều cao biểu đồ. Đọc/ghi float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Trả về hoặc đặt chiều rộng của tiêu đề dưới dạng tỷ lệ của chiều rộng biểu đồ. Đọc/ghi float.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Trả về hoặc đặt chiều rộng của tiêu đề dưới dạng tỷ lệ của chiều rộng biểu đồ. Đọc/ghi float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Trả về hoặc đặt chiều cao của tiêu đề dưới dạng tỷ lệ của chiều cao biểu đồ. Đọc/ghi float.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Trả về hoặc đặt chiều cao của tiêu đề dưới dạng tỷ lệ của chiều cao biểu đồ. Đọc/ghi float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

Phải. Chỉ đọc float.

**Returns:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Duoi. Chỉ đọc float.

**Returns:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Trả về định dạng nhãn dữ liệu. Chỉ đọc [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Lấy hoặc đặt ô dữ liệu workbook. Áp dụng nếu thuộc tính IDataLabelFormat.ShowLabelValueFromCell bằng true.

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Lấy hoặc đặt ô dữ liệu workbook. Áp dụng nếu thuộc tính IDataLabelFormat.ShowLabelValueFromCell bằng true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

Lấy hoặc đặt kiểu hình dạng của nhãn dữ liệu. Trả về [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) nếu không có hình dạng nào được định nghĩa.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Đặt kiểu hình dạng của nhãn dữ liệu đầu tiên thành Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

Lấy hoặc đặt kiểu hình dạng của nhãn dữ liệu. Trả về [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) nếu không có hình dạng nào được định nghĩa.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Đặt kiểu hình dạng của nhãn dữ liệu đầu tiên thành Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Xác định vị trí x thực tế (trai) của phần tử biểu đồ so với goc tren-trai của biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực. Đọc float.

**Returns:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Xác định vị trí y thực tế (tren) của phần tử biểu đồ so với goc tren-trai của biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực. Đọc float.

**Returns:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Xác định chiều rộng thực tế của phần tử biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực. Đọc float.

**Returns:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Xác định chiều cao thực tế của phần tử biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực. Đọc float.

**Returns:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của một FillFormat. Chỉ đọc [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về presentation cha của một FillFormat. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)