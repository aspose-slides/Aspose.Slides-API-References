---
title: IDataLabelCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho các nhãn chuỗi.
type: docs
url: /vi/com.aspose.slides/idatalabelcollection/
---
**Tất cả các giao diện được thực thi:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Biểu diễn các nhãn chuỗi.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy nhãn dữ liệu cho điểm dữ liệu có chỉ mục được chỉ định. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Trả về định dạng mặc định của tất cả các nhãn dữ liệu trong bộ sưu tập. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Biểu diễn định dạng đường dẫn của nhãn dữ liệu. |
| [isVisible()](#isVisible--) | False có nghĩa là nhãn dữ liệu không hiển thị theo mặc định (và vì vậy tất cả các cờ Show*- (ShowValue, ...) của thuộc tính DefaultDataLabelFormat đều là false). |
| [hide()](#hide--) | Ẩn nhãn dữ liệu theo mặc định bằng cách đặt tất cả các cờ Show*- (ShowValue, ...) của thuộc tính DefaultDataLabelFormat ở trạng thái false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Lấy số lượng nhãn dữ liệu hiển thị trong bộ sưu tập. |
| [getCount()](#getCount--) | Lấy số lượng tất cả các nhãn dữ liệu trong bộ sưu tập. |
| [getParentSeries()](#getParentSeries--) | Trả về chuỗi biểu đồ cha. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Trả về chỉ mục của DataLabel được chỉ định trong bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Lấy nhãn dữ liệu cho điểm dữ liệu có chỉ mục được chỉ định.

--------------------

Cách thay thế để truy cập nhãn dữ liệu là: - getSeries().getDataPoints().get_Item(i).getLabel() - quản lý các thuộc tính của nhãn.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Trả về định dạng mặc định của tất cả các nhãn dữ liệu trong bộ sưu tập. Chỉ đọc [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Giá trị trả về:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Biểu diễn định dạng đường dẫn của nhãn dữ liệu. Chỉ đọc [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Giá trị trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False có nghĩa là nhãn dữ liệu không hiển thị theo mặc định (vì vậy tất cả các cờ Show*- (ShowValue, ...) của thuộc tính DefaultDataLabelFormat đều là false). Chỉ đọc  boolean .

--------------------

Nếu nhãn dữ liệu hiển thị theo mặc định, bạn có thể ẩn nó theo mặc định bằng phương thức Hide(). Nhưng nếu nhãn dữ liệu không hiển thị theo mặc định (IsVisible là false) bạn có thể làm nhãn dữ liệu "hiển thị theo mặc định" bằng cách đặt các cờ Show*- (ShowValue, ...) của thuộc tính DefaultDataLabelFormat ở trạng thái true.

**Giá trị trả về:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Ẩn nhãn dữ liệu theo mặc định bằng cách đặt tất cả các cờ Show*- (ShowValue, ...) của thuộc tính DefaultDataLabelFormat ở trạng thái false. IsVisible sẽ là false sau khi thực hiện.

--------------------

Nếu nhãn dữ liệu không hiển thị theo mặc định (IsVisible là false) bạn có thể làm nhãn dữ liệu "hiển thị theo mặc định" bằng cách đặt các cờ Show*- (ShowValue, ...) của thuộc tính DefaultDataLabelFormat ở trạng thái true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Lấy số lượng nhãn dữ liệu hiển thị trong bộ sưu tập. Chỉ đọc  int .

**Giá trị trả về:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lấy số lượng tất cả các nhãn dữ liệu trong bộ sưu tập. Chỉ đọc  int .

**Giá trị trả về:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Trả về chuỗi biểu đồ cha. Chỉ đọc [IChartSeries](../../com.aspose.slides/ichartseries).

**Giá trị trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Trả về chỉ mục của DataLabel được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel cần tìm. |

**Giá trị trả về:**
int - Chỉ mục của một DataLabel hoặc -1 nếu DataLabel không thuộc bộ sưu tập này.