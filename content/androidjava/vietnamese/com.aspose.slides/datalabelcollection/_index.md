---
title: DataLabelCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn các nhãn series.
type: docs
url: /vi/com.aspose.slides/datalabelcollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Biểu diễn các nhãn series.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getChart()](#getChart--) | Trả về biểu đồ cha. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [isVisible()](#isVisible--) | False có nghĩa là nhãn dữ liệu không hiển thị theo mặc định (và do đó tất cả các cờ Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat đều là false). |
| [hide()](#hide--) | Ẩn nhãn dữ liệu theo mặc định bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat ở trạng thái false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Lấy số lượng nhãn dữ liệu hiển thị trong bộ sưu tập. |
| [getCount()](#getCount--) | Lấy số lượng tất cả các nhãn dữ liệu trong bộ sưu tập. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Lấy định dạng nhãn dữ liệu mặc định. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Biểu diễn định dạng đường dẫn nhãn dữ liệu. |
| [getParentSeries()](#getParentSeries--) | Lấy series cha. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Trả về chỉ mục của DataLabel đã chỉ định trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy nhãn dữ liệu cho điểm dữ liệu có chỉ mục đã chỉ định. |
| [getSlide()](#getSlide--) | Trả về slide cha của một FillFormat. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của một FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```


Trả về biểu đồ cha. Chỉ đọc [IChart](../../com.aspose.slides/ichart).

**Trả về:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```


Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False có nghĩa là nhãn dữ liệu không hiển thị theo mặc định (và do đó tất cả các cờ Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat đều là false). Kiểu boolean chỉ đọc.

--------------------

Nếu nhãn dữ liệu hiển thị mặc định, bạn có thể ẩn nó theo mặc định bằng phương thức Hide(). Nhưng nếu nhãn dữ liệu không hiển thị mặc định (IsVisible là false) bạn có thể làm nhãn dữ liệu "hiển thị mặc định" bằng cách đặt các cờ Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat ở trạng thái true.

**Trả về:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Ẩn nhãn dữ liệu theo mặc định bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat ở trạng thái false. IsVisible sẽ là false sau khi thực hiện.

--------------------

Nếu nhãn dữ liệu không hiển thị mặc định (IsVisible là false) bạn có thể làm nhãn dữ liệu "hiển thị mặc định" bằng cách đặt các cờ Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat ở trạng thái true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Lấy số lượng nhãn dữ liệu hiển thị trong bộ sưu tập. Kiểu int chỉ đọc.

**Trả về:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Lấy số lượng tất cả các nhãn dữ liệu trong bộ sưu tập. Kiểu int chỉ đọc.

**Trả về:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


Lấy định dạng nhãn dữ liệu mặc định. Chỉ đọc [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Trả về:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```


Biểu diễn định dạng đường dẫn nhãn dữ liệu. Chỉ đọc [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```


Lấy series cha. Chỉ đọc [IChartSeries](../../com.aspose.slides/ichartseries).

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```


Trả về chỉ mục của DataLabel đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel để tìm. |

**Trả về:**
int - Chỉ mục của một DataLabel hoặc -1 nếu DataLabel không thuộc bộ sưu tập này.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Lấy nhãn dữ liệu cho điểm dữ liệu có chỉ mục đã chỉ định.

--------------------

Cách thay thế để truy cập nhãn dữ liệu là: - series.getDataPoints().get_Item(i).getLabel() - quản lý các thuộc tính nhãn.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IDataLabel](../../com.aspose.slides/idatalabel)
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