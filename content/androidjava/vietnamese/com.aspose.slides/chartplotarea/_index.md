---
title: ChartPlotArea
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho hình chữ nhật nơi biểu đồ sẽ được vẽ.
type: docs
url: /vi/com.aspose.slides/chartplotarea/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartPlotArea](../../com.aspose.slides/ichartplotarea)
```
public class ChartPlotArea extends DomObject<Chart> implements IChartPlotArea
```

Đại diện cho hình chữ nhật nơi biểu đồ sẽ được vẽ.
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getFormat()](#getFormat--) | Trả về định dạng của khu vực vẽ biểu đồ. |
| [getX()](#getX--) | Trả về hoặc đặt tọa độ x của góc trên trái của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều rộng biểu đồ (từ 0 đến 1). |
| [setX(float value)](#setX-float-) | Trả về hoặc đặt tọa độ x của góc trên trái của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều rộng biểu đồ (từ 0 đến 1). |
| [getY()](#getY--) | Trả về hoặc đặt tọa độ y của góc trên trái của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều cao biểu đồ (từ 0 đến 1). |
| [setY(float value)](#setY-float-) | Trả về hoặc đặt tọa độ y của góc trên trái của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều cao biểu đồ (từ 0 đến 1). |
| [getWidth()](#getWidth--) | Trả về hoặc đặt chiều rộng của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều rộng biểu đồ (từ 0 đến 1). |
| [setWidth(float value)](#setWidth-float-) | Trả về hoặc đặt chiều rộng của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều rộng biểu đồ (từ 0 đến 1). |
| [getHeight()](#getHeight--) | Trả về hoặc đặt chiều cao của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều cao biểu đồ (từ 0 đến 1). |
| [setHeight(float value)](#setHeight-float-) | Trả về hoặc đặt chiều cao của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều cao biểu đồ (từ 0 đến 1). |
| [getRight()](#getRight--) | Bên phải. |
| [getBottom()](#getBottom--) | Bên dưới. |
| [getChart()](#getChart--) | Biểu đồ. |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | Xác định cách vị trí sẽ được tính: true \\u2013 tính tự động; được định nghĩa bởi các thuộc tính X, Y, Width, Height. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Nếu bố cục khu vực vẽ được xác định thủ công, thuộc tính này chỉ định việc bố trí khu vực vẽ theo bên trong (không bao gồm trục và nhãn trục) hay bên ngoài (bao gồm trục và nhãn trục). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Nếu bố cục khu vực vẽ được xác định thủ công, thuộc tính này chỉ định việc bố trí khu vực vẽ theo bên trong (không bao gồm trục và nhãn trục) hay bên ngoài (bao gồm trục và nhãn trục). |
| [getActualX()](#getActualX--) | Xác định vị trí x thực tế (trái) của phần tử biểu đồ so với góc trái trên của biểu đồ. |
| [getActualY()](#getActualY--) | Xác định vị trí y thực tế (trên) của phần tử biểu đồ so với góc trái trên của biểu đồ. |
| [getActualWidth()](#getActualWidth--) | Xác định chiều rộng thực tế của phần tử biểu đồ. |
| [getActualHeight()](#getActualHeight--) | Xác định chiều cao thực tế của phần tử biểu đồ. |
| [getSlide()](#getSlide--) | Trả về slide cha của một FillFormat. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của một FillFormat. |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Trả về định dạng của khu vực vẽ biểu đồ. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)

### getX() {#getX--}
```
public final float getX()
```

Trả về hoặc đặt tọa độ x của góc trên trái của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều rộng biểu đồ (từ 0 đến 1). Đọc/ghi float.

**Trả về:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Trả về hoặc đặt tọa độ x của góc trên trái của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều rộng biểu đồ (từ 0 đến 1). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Trả về hoặc đặt tọa độ y của góc trên trái của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều cao biểu đồ (từ 0 đến 1). Đọc/ghi float.

**Trả về:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Trả về hoặc đặt tọa độ y của góc trên trái của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều cao biểu đồ (từ 0 đến 1). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Trả về hoặc đặt chiều rộng của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều rộng biểu đồ (từ 0 đến 1). Đọc/ghi float.

**Trả về:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Trả về hoặc đặt chiều rộng của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều rộng biểu đồ (từ 0 đến 1). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Trả về hoặc đặt chiều cao của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều cao biểu đồ (từ 0 đến 1). Đọc/ghi float.

**Trả về:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Trả về hoặc đặt chiều cao của hộp giới hạn khu vực vẽ biểu đồ như một phần của chiều cao biểu đồ (từ 0 đến 1). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

Bên phải. Chỉ đọc float.

**Trả về:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

Bên dưới. Chỉ đọc float.

**Trả về:**
float

### getChart() {#getChart--}
```
public final IChart getChart()
```

Biểu đồ. Chỉ đọc [IChart](../../com.aspose.slides/ichart).

**Trả về:**
[IChart](../../com.aspose.slides/ichart)

### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```

Xác định cách vị trí sẽ được tính: true \\u2013 tính tự động; được định nghĩa bởi các thuộc tính X, Y, Width, Height. Chỉ đọc boolean.

**Trả về:**
boolean

### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
```

Nếu bố cục khu vực vẽ được xác định thủ công, thuộc tính này chỉ định việc bố trí khu vực vẽ theo bên trong (không bao gồm trục và nhãn trục) hay bên ngoài (bao gồm trục và nhãn trục). Đọc/ghi [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**Trả về:**
int

### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public final void setLayoutTargetType(int value)
```

Nếu bố cục khu vực vẽ được xác định thủ công, thuộc tính này chỉ định việc bố trí khu vực vẽ theo bên trong (không bao gồm trục và nhãn trục) hay bên ngoài (bao gồm trục và nhãn trục). Đọc/ghi [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Xác định vị trí x thực tế (trái) của phần tử biểu đồ so với góc trái trên của biểu đồ. Gọi IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Đọc float.

**Trả về:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Xác định vị trí y thực tế (trên) của phần tử biểu đồ so với góc trái trên của biểu đồ. Gọi IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Đọc float.

**Trả về:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Xác định chiều rộng thực tế của phần tử biểu đồ. Gọi IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Đọc float.

**Trả về:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Xác định chiều cao thực tế của phần tử biểu đồ. Gọi IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Đọc float.

**Trả về:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của một FillFormat. Chỉ đọc [BaseSlide](../../com.aspose.slides/baseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của một FillFormat. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)