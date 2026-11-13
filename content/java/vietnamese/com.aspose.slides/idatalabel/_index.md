---
title: IDataLabel
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các nhãn của chuỗi.
type: docs
url: /vi/com.aspose.slides/idatalabel/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Biểu diễn các nhãn của chuỗi.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isVisible()](#isVisible--) | False có nghĩa là nhãn dữ liệu không hiển thị (và do đó tất cả các cờ Show*-flags (ShowValue, ...) đều là false). |
| [hide()](#hide--) | Ẩn nhãn dữ liệu bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) ở trạng thái false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Trả về định dạng của nhãn dữ liệu. |
| [getValueFromCell()](#getValueFromCell--) | Lấy hoặc đặt ô dữ liệu workbook. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Lấy hoặc đặt ô dữ liệu workbook. |
| [getActualLabelText()](#getActualLabelText--) | Trả về văn bản nhãn thực tế dựa trên cài đặt DataLabelFormat hoặc giá trị TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | Lấy hoặc đặt kiểu hình dạng của nhãn dữ liệu. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Lấy hoặc đặt kiểu hình dạng của nhãn dữ liệu. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False có nghĩa là nhãn dữ liệu không hiển thị (và do đó tất cả các cờ Show*-flags (ShowValue, ...) đều là false). Boolean chỉ đọc.

--------------------

Nếu nhãn dữ liệu hiển thị, bạn có thể ẩn nó bằng phương thức Hide(). Nhưng nếu nhãn dữ liệu không hiển thị (IsVisible là false) bạn có thể làm cho nhãn dữ liệu hiển thị bằng cách đặt các cờ Show*-flags (ShowValue, ...) ở trạng thái true.

**Trả về:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Ẩn nhãn dữ liệu bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) ở trạng thái false. IsVisible sẽ là false sau thao tác này.

--------------------

Nếu nhãn dữ liệu không hiển thị (IsVisible là false) bạn có thể làm cho nhãn dữ liệu hiển thị bằng cách đặt các cờ Show*-flags (ShowValue, ...) ở trạng thái true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Trả về định dạng của nhãn dữ liệu. Chỉ đọc [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Trả về:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Lấy hoặc đặt ô dữ liệu workbook. Áp dụng nếu thuộc tính IDataLabelFormat.ShowLabelValueFromCell bằng true.

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Lấy hoặc đặt ô dữ liệu workbook. Áp dụng nếu thuộc tính IDataLabelFormat.ShowLabelValueFromCell bằng true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Trả về văn bản nhãn thực tế dựa trên cài đặt DataLabelFormat hoặc giá trị TextFrameForOverriding.Text.

**Trả về:**
java.lang.String - Chuỗi văn bản nhãn thực tế
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Lấy hoặc đặt kiểu hình dạng của nhãn dữ liệu. Trả về [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) nếu không có hình dạng nào được định nghĩa.

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

**Trả về:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Lấy hoặc đặt kiểu hình dạng của nhãn dữ liệu. Trả về [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) nếu không có hình dạng nào được định nghĩa.

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

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |